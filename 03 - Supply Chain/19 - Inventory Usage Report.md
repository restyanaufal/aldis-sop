---
nomor: 19
kategori: Supply Chain
pic: SCM & Store Leader
frekuensi: Harian (dicatat saat tutup)
waktu_pengerjaan: 10–15 menit
status: Draft
versi: 2.0
terakhir_diperbarui: 2026-06-13
---

# Inventory Usage Report

> Dokumen terkait: [[21 - Waste Analysis Report]] · [[22 - Next Day Preparation List]] · [[24 - Blok M Ponpin Integration SOP]]

## Tujuan
Mencatat pemakaian stok harian dan membandingkan dengan pemakaian teoritis berdasarkan jumlah penjualan — mendeteksi selisih yang bisa mengindikasikan over-portioning, waste tersembunyi, atau kehilangan.

---

## Form Harian

**Tanggal:** __________ | **Outlet:** __________ | **Total Struk Hari Ini:** __________ | **Dicatat oleh:** __________

| Produk | Stok Awal | Terima | Total Tersedia | Terpakai Aktual | Waste | Stok Akhir | Teoritis* | Variansi | Status |
|--------|-----------|--------|----------------|-----------------|-------|------------|-----------|---------|--------|
| Patty Reguler | | | | | | | | | |
| Patty Medium | | | | | | | | | |
| Sosis | | | | | | | | | |
| Odading / Bun Reguler | | | | | | | | | |
| Bun Medium | | | | | | | | | |
| Nugget Chicken | | | | | | | | | |
| Lettuce (gram) | | | | | | | | | |
| Kyuri / Timun (pcs) | | | | | | | | | |
| Tomat (pcs) | | | | | | | | | |
| Mayo (gram) | | | | | | | | | |
| BBQ Sauce (gram) | | | | | | | | | |
| Bahan Punten | | | | | | | | | |
| Box makanan | | | | | | | | | |
| Cup + Cup Seal | | | | | | | | | |

---

## Cara Hitung Kolom Teoritis & Variansi

**Teoritis** = jumlah yang seharusnya terpakai berdasarkan struk penjualan × gramasi standar

### Referensi Gramasi per Produk (dari [[13 - Standard Recipe Book]])

| Bahan | Per Porsi | Produk yang Pakai |
|-------|-----------|------------------|
| Patty Reguler | 1 pcs | Noel Burger, Odadog Paus Jumbo |
| Patty Medium | 1 pcs | Liam Burger |
| Sosis | 1 pcs | Odading Rudal Iran |
| Nugget | 2 pcs | Odadog Chicken Jumbo |
| Odading/Bun | 1 pcs | sesuai produk |
| Lettuce | 20 gr | semua produk |
| Kyuri/Timun | 2 pcs | semua produk |
| Tomat | 2 pcs | semua produk |
| Mayo | 60 gr | semua produk |
| BBQ Sauce | 20 gr | semua produk |

**Contoh hitung:**
- Hari ini terjual: 200 Liam Burger
- Teoritis Patty Medium = 200 × 1 pcs = **200 pcs**
- Aktual terpakai = 215 pcs
- **Variansi = 215 − 200 = +15 pcs (over)**

**Rumus:**
```
Variansi = Terpakai Aktual − Teoritis
Variansi % = (Variansi ÷ Teoritis) × 100%
```

---

## Threshold Variansi

| Variansi % | Status | Tindakan |
|-----------|--------|---------|
| ≤ 5% | ✅ Normal | Tidak ada tindakan |
| 6–15% | ⚠️ Perhatikan | Cek porsi, cek waste — catat keterangan |
| > 15% | ❌ Investigasi | Leader wajib lapor Manager hari ini — cek penyebab |

> Variansi negatif (terpakai lebih sedikit dari teoritis) juga perlu dicek — bisa berarti porsi kurang atau ada transaksi yang tidak tercatat.

---

## Rumus Stok

```
Stok Awal + Terima = Total Tersedia
Total Tersedia − Stok Akhir = Terpakai Aktual + Waste
Terpakai Aktual = (Total Tersedia − Stok Akhir) − Waste
```

---

## Reorder Level (Minimum Stok)

| Produk | Reorder Level | Keterangan |
|--------|--------------|------------|
| Patty Reguler | < 30 pcs | Pesan jika di bawah ini |
| Patty Medium | < 30 pcs | |
| Sosis | < 20 pcs | |
| Odading / Bun | < 20 pcs | Tergantung jadwal CPNB |
| Nugget | < 20 pcs | |
| Lettuce | < 2 box | |
| Kyuri | < 1 box | |

> Sesuaikan reorder level dengan rata-rata penjualan aktual outlet masing-masing.

---

## Cara Kirim Laporan ke SCM

Setiap hari tutup:
1. Foto form yang sudah terisi
2. Kirim ke WhatsApp group SCM + Store Leader
3. Tandai baris yang "Reorder: Ya" dengan pesan: *"Minta restock: [nama item] [jumlah]"*
4. Jika ada variansi > 15%, tandai dengan: *"⚠️ Variansi tinggi: [item] — perlu cek"*

---

## Standar Kelulusan
Form terisi setiap hari. Kolom Teoritis dan Variansi dihitung. Variansi > 15% dilaporkan ke Manager.

---

## Catatan / Versi
- v1.0 (2026-06-12): Draft awal — fundamental multi-outlet
- v2.0 (2026-06-13): Tambah kolom Teoritis + Variansi + threshold investigasi variansi
