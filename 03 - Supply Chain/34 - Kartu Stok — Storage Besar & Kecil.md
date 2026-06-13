---
nomor: 34
kategori: Supply Chain
pic: Store Leader · SCM / Gudang
frekuensi: Setiap kali ada perpindahan stok antar storage
waktu_pengerjaan: 2–5 menit per transaksi
status: Draft
versi: 1.0
terakhir_diperbarui: 2026-06-13
---

# Kartu Stok — Storage Besar & Kecil

> Dokumen terkait: [[04 - FIFO Monitoring Sheet]] · [[19 - Inventory Usage Report]] · [[03 - Delivery Order]] · [[22 - Next Day Preparation List]]

## Tujuan

Memastikan pergerakan stok antara **Storage Besar (Gudang)** dan **Storage Kecil (Outlet)** tercatat akurat setiap saat — sehingga:
1. Saldo stok selalu bisa dicek tanpa harus hitung fisik ulang
2. Pengambilan dilakukan dalam **kelipatan standar (20 atau 30 pcs)** agar pencatatan mudah dan konsisten
3. Tidak ada selisih stok yang tidak bisa dijelaskan

---

## Definisi Storage

| Storage | Lokasi | PIC | Isi |
|---------|--------|-----|-----|
| **Storage Besar** | Gudang / CK | SCM / Gudang | Stok induk — semua bahan baku dalam jumlah besar |
| **Storage Kecil** | Dalam outlet | Store Leader | Stok operasional harian outlet |

> Perpindahan stok selalu searah: **Storage Besar → Storage Kecil**. Tidak ada transfer balik kecuali dalam kondisi khusus (retur cacat, over-stok outlet).

---

## Aturan Kelipatan Pengambilan

Setiap pengambilan dari Storage Besar ke Storage Kecil **wajib** dalam kelipatan standar:

| Jenis Produk | Kelipatan Standar | Contoh Valid | Contoh Tidak Valid |
|--------------|------------------|--------------|-------------------|
| Patty / Daging | **20 pcs** | 20, 40, 60, 80, 100 | 15, 35, 47 |
| Sosis | **20 pcs** | 20, 40, 60, 80, 100 | 25, 55, 90 |
| Bahan kemasan (box, wrapper) | **20 atau 30 pcs** | 20, 30, 60, 90 | 10, 25, 45 |
| Consumable (gloves, cup, dll) | **30 pcs / 1 pak** | 30, 60, 90 | 10, 25 |
| Bahan cair (saus, minyak) | **per botol / per liter** | 1L, 2L, 5L | 0.7L, 1.3L |

**Alasan kelipatan standar:**
- Menghilangkan ambiguitas saat penghitungan
- Memudahkan verifikasi: jika saldo tidak pas kelipatan → ada yang salah catat atau hilang
- Mempercepat proses serah terima antar shift

---

## Format Kartu Stok

Setiap jenis produk memiliki **kartu stok sendiri**. Kartu bisa berupa:
- Kertas fisik (ditempel/digantung dekat storage)
- Google Sheet per outlet (direkomendasikan untuk audit)

### Kolom Kartu Stok

| Kolom | Keterangan |
|-------|------------|
| **Tanggal** | Tanggal transaksi |
| **Jam** | Jam transaksi (penting untuk audit) |
| **Keterangan** | Sumber / tujuan perpindahan stok |
| **Masuk** | Jumlah masuk ke storage ini (kelipatan standar) |
| **Keluar** | Jumlah keluar dari storage ini |
| **Saldo** | Masuk − Keluar = Saldo saat ini |
| **PIC** | Inisial yang melakukan & yang menerima |

---

## Kartu Stok Storage Besar (Gudang)

**Produk:** __________ | **Satuan:** __________ | **Bulan:** __________

| Tgl | Jam | Keterangan | Masuk | Keluar | Saldo | PIC Gudang | PIC Penerima |
|-----|-----|-----------|-------|--------|-------|------------|--------------|
| | | Saldo awal bulan | | | | | |
| | | Dari: DO / Supplier | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | Ke outlet: __________ | | | | | |
| | | **Saldo akhir bulan** | | | **=** | | |

---

## Kartu Stok Storage Kecil (Outlet)

**Produk:** __________ | **Outlet:** __________ | **Bulan:** __________

| Tgl | Jam | Keterangan | Masuk | Keluar | Saldo | PIC |
|-----|-----|-----------|-------|--------|-------|-----|
| | | Saldo awal | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | Dari gudang (+20/30) | | | | |
| | | Pemakaian harian | | | | |
| | | **Saldo akhir** | | | **=** | |

---

## Prosedur Pengambilan Stok (Storage Besar → Storage Kecil)

### Step 1 — Tentukan Kebutuhan

- [ ] Cek saldo saat ini di Storage Kecil
- [ ] Estimasi kebutuhan sampai pengambilan berikutnya
- [ ] Hitung jumlah yang perlu diambil → **bulatkan ke kelipatan standar terdekat**

```
Contoh:
- Saldo sekarang: 15 pcs patty
- Estimasi kebutuhan besok: 90 pcs
- Defisit: 90 - 15 = 75 pcs
- Kelipatan 20: 75 → ambil 80 pcs (4 × 20)
```

### Step 2 — Ambil & Serah Terima

- [ ] PIC Gudang keluarkan stok sesuai jumlah yang disepakati
- [ ] PIC Outlet hitung fisik di depan PIC Gudang — **jangan langsung percaya tanpa hitung**
- [ ] Keduanya setuju jumlah → tanda tangan / inisial di kartu stok masing-masing

### Step 3 — Catat di Dua Kartu Sekaligus

| Kartu Storage Besar | Kartu Storage Kecil |
|--------------------|---------------------|
| Catat di kolom **Keluar** | Catat di kolom **Masuk** |
| Saldo Besar berkurang | Saldo Kecil bertambah |
| Keterangan: "Ke outlet [nama]" | Keterangan: "Dari gudang" |

> **Aturan:** Kedua kartu dicatat **pada saat yang sama**, bukan nanti-nanti.

### Step 4 — FIFO

- [ ] Stok lama selalu ada di depan / dipakai lebih dulu
- [ ] Saat menaruh stok baru di Storage Kecil, push stok lama ke depan
- [ ] Cek tanggal expired saat serah terima

---

## Jadwal Rekonsiliasi

| Frekuensi | Kegiatan | PIC |
|-----------|----------|-----|
| **Setiap minggu** | Hitung fisik Storage Kecil → cocokan dengan saldo kartu stok | Store Leader |
| **Setiap akhir bulan** | Hitung fisik Storage Besar → cocokan dengan saldo kartu stok | SCM / Gudang |
| **Kapan pun ada selisih** | Investigasi segera — jangan tunggu rekonsiliasi bulanan | Store Leader + Manager |

### Toleransi Selisih

| Selisih | Tindakan |
|---------|----------|
| 0 pcs | ✅ Normal |
| 1–2 pcs | Cari penyebab, catat sebagai catatan di kartu |
| 3–5 pcs | Lapor Manager — kemungkinan ada transaksi yang tidak dicatat |
| > 5 pcs | Investigasi penuh — audit semua transaksi bulan berjalan |

---

## Penyebab Selisih yang Umum (dan Cara Cegah)

| Penyebab | Pencegahan |
|----------|-----------|
| Lupa catat transaksi | Catat **saat transaksi terjadi**, bukan di akhir hari |
| Salah hitung saat serah terima | Hitung ulang bersama sebelum tanda tangan |
| Ambil tidak dalam kelipatan standar | Ingatkan: selalu kelipatan 20 atau 30 |
| Barang rusak/expired tidak dicatat sebagai keluar | Disposal wajib masuk kolom keluar dengan keterangan "Rusak/Expired" |
| Satu produk pakai kartu berbeda | Pastikan 1 kartu = 1 SKU produk, konsisten |

---

## Standar Kelulusan

SOP ini berjalan benar jika:
1. Setiap pengambilan tercatat di kedua kartu (Storage Besar dan Kecil) pada hari yang sama
2. Semua pengambilan dalam kelipatan standar — tidak ada angka ganjil
3. Rekonsiliasi mingguan selisih ≤ 2 pcs untuk semua SKU
4. Tidak ada kartu stok yang tertinggal lebih dari 2 hari tanpa pencatatan

---

## Catatan / Versi
- v1.0 (2026-06-13): Dokumen baru — sistem kartu stok dua-level (Storage Besar & Kecil); pengambilan kelipatan 20/30 pcs untuk kemudahan pencatatan dan audit
