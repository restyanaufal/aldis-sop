---
nomor: 19
kategori: Supply Chain
pic: Kepala Dapur
frekuensi: Harian (dicatat saat tutup)
waktu_pengerjaan: 10–15 menit
status: Draft
versi: 1.0
terakhir_diperbarui: 2026-08-13
---

# Inventory Usage Report — Tegalega

> Dokumen terkait: [[21 - Waste Analysis Report]] · [[22 - Next Day Preparation List]]

## Tujuan
Mencatat pemakaian bahan harian dan membandingkan dengan pemakaian teoritis berdasarkan jumlah paket terjual — mendeteksi selisih yang bisa mengindikasikan over-portioning atau waste tersembunyi.

---

## Form Harian

**Tanggal:** __________ | **Total Paket Terjual:** __________ | **Dicatat oleh:** __________

| Bahan | Stok Awal | Beli Hari Ini | Total Tersedia | Terpakai Aktual | Waste | Stok Akhir | Teoritis* | Variansi |
|-------|-------------|------------------|-------------------|--------------------|-------|--------------|-----------|-----------|
| Ayam (potong) | | | | | | | | |
| Paru (pcs) | | | | | | | | |
| Babat (pcs) | | | | | | | | |
| Koyor (pcs) | | | | | | | | |
| Ati Ampela (pcs) | | | | | | | | |
| Beras (kg) | | | | | | | | |
| Jukut (gram) | | | | | | | | |
| Box makanan (pcs) | | | | | | | | |

---

## Cara Hitung Kolom Teoritis & Variansi

**Teoritis** = jumlah yang seharusnya terpakai berdasarkan jumlah paket terjual × komposisi standar dari [[13 - Standard Recipe Book]]

**Contoh hitung:**
- Hari ini terjual: 10 Paket Ayam Basah
- Teoritis Ayam Goreng Basah = 10 × 1 potong = **10 potong**
- Aktual terpakai = 11 potong
- **Variansi = 11 − 10 = +1 potong (over)**

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
| > 15% | ❌ Investigasi | Kepala Dapur cek penyebab hari itu juga |

---

## Rumus Stok

```
Stok Awal + Beli Hari Ini = Total Tersedia
Total Tersedia − Stok Akhir = Terpakai Aktual + Waste
Terpakai Aktual = (Total Tersedia − Stok Akhir) − Waste
```

---

## Standar Kelulusan
Form terisi setiap hari. Kolom Teoritis dan Variansi dihitung. Variansi > 15% diinvestigasi hari itu juga.

---

## Catatan / Versi
- v1.0 (2026-08-13): Draft awal — diadaptasi dari SOP Aldis Hotdog untuk operasional 1 titik Tegalega
