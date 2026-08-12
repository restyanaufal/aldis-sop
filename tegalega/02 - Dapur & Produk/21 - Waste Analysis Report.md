---
nomor: 21
kategori: Dapur & Produk
pic: Kepala Dapur
frekuensi: Harian (dicatat saat tutup) + rekap mingguan setiap Senin
waktu_pengerjaan: 5–10 menit
status: Draft
versi: 1.0
terakhir_diperbarui: 2026-08-13
---

# Waste Analysis Report — Tegalega

> Dokumen terkait: [[19 - Inventory Usage Report]] · [[05 - Food Safety Checklist]] · [[04 - FIFO Monitoring Sheet]]

## Tujuan
Mencatat dan menganalisis pemborosan bahan setiap hari — data untuk memperbaiki estimasi belanja, menekan food cost, dan mendeteksi masalah produksi.

## Target Industri FnB
**Waste rate ≤ 3% dari total food cost harian** — angka di atas ini menandakan ada masalah yang perlu diselesaikan.

---

## Form Harian

**Tanggal:** __________ | **Total Paket Terjual:** __________ | **Dicatat oleh:** __________

| Kategori Waste | Item | Jumlah Terbuang | Satuan | Est. Harga Satuan | Est. Biaya Waste | Alasan |
|------------------|------|------------------|--------|---------------------|---------------------|--------|
| Protein | Ayam | | potong | Rp | Rp | |
| Jeroan | Paru / Babat / Koyor / Ati Ampela | | pcs | Rp | Rp | |
| Nasi | Nasi sisa | | porsi | Rp | Rp | |
| Sayuran | Jukut (selada air) | | gram | Rp | Rp | |
| Sambal | Sambal dadak/bawang | | porsi | Rp | Rp | |
| Kemasan | Box / plastik | | pcs | Rp | Rp | |
| Paket Jadi | Paket tidak terjual | | pcs | Rp | Rp | |
| | | | | **TOTAL WASTE** | **Rp** | |

---

## Kode Alasan Waste

| Kode | Alasan | Contoh |
|------|--------|--------|
| **A** | Bahan busuk sebelum dipakai | Jeroan sudah berbau sebelum sempat dimasak |
| **B** | Overproduction | Masak terlalu banyak, tidak terjual habis |
| **C** | Kerusakan fisik / kesalahan masak | Gosong, kurang matang lalu dibuang, nasi basi |
| **D** | Kesalahan proses | Salah rakit paket, salah order, jatuh |
| **E** | Bahan tidak layak saat beli | Bahan sudah kurang segar sejak dibeli |

---

## Cara Hitung Waste Rate %

```
Total Food Cost Harian = perkiraan COGS untuk semua paket terjual hari ini (lihat referensi COGS di Tegalega BOM & Costing)

Waste Rate % = (Total Biaya Waste ÷ Total Food Cost Harian) × 100%
```

**Referensi COGS per Paket** (lihat [[Tegalega BOM & Costing]] untuk update terbaru):

| Paket | Est. COGS |
|-------|-----------|
| Paket Ayam Basah Tegalega | ± Rp 17.775 |
| Paket Ayam Goreng Gurih Tegalega | ± Rp 17.527 |

---

## Threshold & Status Waste Rate

| Waste Rate | Status | Tindakan |
|-----------|--------|---------|
| **≤ 2%** | ✅ Excellent | Pertahankan |
| **2–3%** | ✅ Normal | Monitor terus |
| **3–5%** | ⚠️ Perhatikan | Investigasi penyebab terbesar |
| **> 5%** | ❌ Kritis | Analisis mendalam — ada masalah sistemik |

---

## Langkah Analisis Mingguan

Kepala Dapur rekap setiap **Senin pagi** untuk minggu sebelumnya:

- [ ] Hitung total waste per kategori selama 7 hari
- [ ] Hitung Waste Rate % rata-rata minggu ini
- [ ] Identifikasi alasan terbanyak (A/B/C/D/E)
- [ ] Ambil 1 tindakan konkret untuk alasan waste terbesar
- [ ] Laporkan ke Owner

### Template Rekap Mingguan

**Minggu ke-** __ | **Periode:** __________ s/d __________

| Hari | Total Waste (Rp) | Est. Food Cost (Rp) | Waste Rate % |
|------|---------------------|------------------------|----------------|
| Senin | | | % |
| Selasa | | | % |
| Rabu | | | % |
| Kamis | | | % |
| Jumat | | | % |
| Sabtu | | | % |
| Minggu | | | % |
| **Total** | **Rp** | **Rp** | **%** |

**Alasan waste terbanyak minggu ini:** Kode __ — __________
**Tindakan yang diambil:** __________

---

## Standar Kelulusan
Report terisi setiap hari tutup. Rekap mingguan dikirim ke Owner setiap Senin.

## Catatan / Versi
- v1.0 (2026-08-13): Draft awal — diadaptasi dari SOP Aldis Hotdog, kategori waste disesuaikan menu Tegalega
