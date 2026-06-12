---
nomor: 19
kategori: Supply Chain
pic: SCM & Store Leader
frekuensi: Harian (dicatat saat tutup)
waktu_pengerjaan: 10 menit
status: Draft
versi: 1.0
terakhir_diperbarui: 2026-06-12
---

# Inventory Usage Report

## Tujuan
Mencatat pemakaian stok harian — sebagai dasar untuk menentukan jumlah order berikutnya dan mendeteksi kehilangan yang tidak wajar.

## Kapan Digunakan
Setiap akhir hari operasional, oleh Store Leader atau crew piket.

---

## Form Harian

**Tanggal:** __________ | **Outlet:** __________ | **Dicatat oleh:** __________

| Produk | Stok Awal Hari Ini | Penerimaan Hari Ini | Total Tersedia | Terpakai | Waste | Stok Akhir | Reorder? |
|--------|-------------------|---------------------|----------------|----------|-------|------------|----------|
| Patty Medium | | | | | | | Ya / Tidak |
| Patty Small | | | | | | | Ya / Tidak |
| Sosis Elprimo | | | | | | | Ya / Tidak |
| Odading / Roti | | | | | | | Ya / Tidak |
| Bun Medium | | | | | | | Ya / Tidak |
| Bun Small | | | | | | | Ya / Tidak |
| Kol putih (gram) | | | | | | | Ya / Tidak |
| Tomat (gram) | | | | | | | Ya / Tidak |
| Timun Kyuri (gram) | | | | | | | Ya / Tidak |
| Mayo (gram) | | | | | | | Ya / Tidak |
| BBQ Sauce (gram) | | | | | | | Ya / Tidak |
| Bahan Punten | | | | | | | Ya / Tidak |
| Box makanan | | | | | | | Ya / Tidak |
| Cup + Cup Seal | | | | | | | Ya / Tidak |

---

## Rumus Sederhana

```
Stok Awal + Penerimaan = Total Tersedia
Total Tersedia - Stok Akhir = Terpakai + Waste
```

Jika **Terpakai + Waste** jauh melebihi jumlah produk yang terjual → ada yang perlu diinvestigasi (over-portioning, waste tersembunyi, atau kehilangan).

---

## Reorder Level (Minimum Stok)

| Produk | Reorder Level | Keterangan |
|--------|--------------|------------|
| Patty Medium | < 30 pcs | Pesan jika di bawah ini |
| Patty Small | < 20 pcs | |
| Sosis | < 20 pcs | |
| Odading | < 20 pcs | Tergantung jadwal CPNB |
| Bun (Medium / Small) | < 20 pcs masing-masing | |
| Sayuran segar | < 500 gram | Beli tiap 2–3 hari |

> Reorder level ini adalah baseline awal — sesuaikan dengan rata-rata penjualan harian outlet masing-masing.

---

## Cara Kirim Laporan ke SCM

Setiap hari tutup:
1. Foto form yang sudah terisi
2. Kirim ke WhatsApp group SCM + Store Leader
3. Tandai baris yang "Reorder: Ya" dengan pesan: *"Minta restock: [nama item] [jumlah]"*

---

## Standar Kelulusan
Form terisi setiap hari tanpa ada kolom kosong yang seharusnya diisi.

## Catatan / Versi
- v1.0 (2026-06-12): Draft awal — fundamental multi-outlet
