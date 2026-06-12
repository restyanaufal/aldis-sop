---
nomor: 21
kategori: Dapur & Produk
pic: Store Leader
frekuensi: Harian (dicatat saat tutup) + rekap mingguan setiap Senin
waktu_pengerjaan: 5–10 menit
status: Draft
versi: 2.0
terakhir_diperbarui: 2026-06-13
---

# Waste Analysis Report

> Dokumen terkait: [[19 - Inventory Usage Report]] · [[05 - Food Safety Checklist]] · [[04 - FIFO Monitoring Sheet]]

## Tujuan
Mencatat dan menganalisis pemborosan bahan setiap hari — sebagai data untuk memperbaiki forecast pemesanan, menekan food cost, dan mendeteksi masalah produksi.

## Target Industri FnB
**Waste rate ≤ 3% dari total food cost harian** — angka di atas ini menandakan ada masalah yang perlu diselesaikan.

---

## Form Harian

**Tanggal:** __________ | **Outlet:** __________ | **Total Struk:** __________ | **Dicatat oleh:** __________

| Kategori Waste | Item | Jumlah Terbuang | Satuan | Est. Harga Satuan | Est. Biaya Waste | Alasan |
|----------------|------|-----------------|--------|------------------|-----------------|--------|
| Protein | Patty | | pcs | Rp | Rp | |
| Protein | Sosis | | pcs | Rp | Rp | |
| Protein | Nugget | | pcs | Rp | Rp | |
| Roti / Bun | Odading / Bun | | pcs | Rp | Rp | |
| Sayuran | Lettuce | | gram | Rp | Rp | |
| Sayuran | Kyuri / Tomat | | pcs | Rp | Rp | |
| Kondimen | Mayo / BBQ Sauce | | gram | Rp | Rp | |
| Minuman | Bahan Punten | | serving | Rp | Rp | |
| Kemasan | Box / Plastik / Cup | | pcs | Rp | Rp | |
| Produk Jadi | Produk tidak terjual | | pcs | Rp | Rp | |
| | | | | **TOTAL WASTE** | **Rp** | |

---

## Kode Alasan Waste

| Kode | Alasan | Contoh |
|------|--------|--------|
| **A** | Kadaluarsa / expired | Bahan lewat tanggal — FIFO tidak dijalankan |
| **B** | Overproduction | Masak terlalu banyak, tidak terjual |
| **C** | Kerusakan fisik | Roti remuk, patty gosong, sayuran layu |
| **D** | Kesalahan proses | Salah rakit, salah order, produk jatuh |
| **E** | Bahan tidak layak saat terima | Datang dalam kondisi rusak dari CPNB/supplier |

---

## Cara Hitung Waste Rate %

```
Total Food Cost Harian = perkiraan biaya bahan untuk semua produk terjual hari ini

Waste Rate % = (Total Biaya Waste ÷ Total Food Cost Harian) × 100%
```

**Estimasi Food Cost per Porsi (referensi kasar):**

| Produk | Est. Food Cost |
|--------|---------------|
| Odading Rudal Iran | Rp 8.000–10.000 |
| Odadog Paus / Chicken | Rp 9.000–11.000 |
| Noel Burger | Rp 10.000–12.000 |
| Liam Burger | Rp 11.000–13.000 |

> *(Angka ini perlu dikonfirmasi dengan data COGS aktual dari Finance.)*

**Contoh Hitung:**
- Total struk = 300 porsi, avg food cost Rp 10.000 → Total Food Cost = Rp 3.000.000
- Total biaya waste = Rp 120.000
- **Waste Rate = (120.000 ÷ 3.000.000) × 100% = 4%** → Perlu perhatian

---

## Threshold & Status Waste Rate

| Waste Rate | Status | Tindakan |
|-----------|--------|---------|
| **≤ 2%** | ✅ Excellent | Pertahankan |
| **2–3%** | ✅ Normal | Monitor terus |
| **3–5%** | ⚠️ Perhatikan | Investigasi penyebab terbesar, ambil tindakan minggu ini |
| **> 5%** | ❌ Kritis | Lapor Manager segera — analisis mendalam, ada masalah sistemik |

---

## Ambang Batas Waste per Item (Harian)

| Kategori | Batas Wajar | Perlu Investigasi |
|----------|-------------|------------------|
| Patty / Sosis / Nugget | ≤ 5 pcs/hari | > 5 pcs — cek forecast & produksi |
| Sayuran total | ≤ 300 gram/hari | > 300 gram — cek porsi atau volume pembelian |
| Produk jadi tidak terjual | 0 pcs ideal | > 2 pcs — cek production planning |

---

## Langkah Analisis Mingguan

Store Leader rekap setiap **Senin pagi** untuk minggu sebelumnya:

- [ ] Hitung total waste per kategori selama 7 hari
- [ ] Hitung **Waste Rate % rata-rata minggu ini**
- [ ] Identifikasi alasan terbanyak (A/B/C/D/E)
- [ ] Bandingkan dengan minggu sebelumnya — naik atau turun?
- [ ] Ambil **1 tindakan konkret** untuk alasan waste terbesar
- [ ] Laporkan ke Manager / Bisnis Development

### Template Rekap Mingguan

**Minggu ke-** __ | **Periode:** __________ s/d __________

| Hari | Total Waste (Rp) | Est. Food Cost (Rp) | Waste Rate % |
|------|-----------------|---------------------|-------------|
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
**Target minggu depan:** Waste rate ≤ ___%

---

## Standar Kelulusan
Report terisi setiap hari tutup. Waste Rate dihitung setiap hari. Rekap mingguan dikirim ke Manager setiap Senin.

---

## Catatan / Versi
- v1.0 (2026-06-12): Draft awal — fundamental multi-outlet
- v2.0 (2026-06-13): Tambah perhitungan Waste Rate %, threshold industri FnB, referensi food cost, rekap mingguan dengan trending
