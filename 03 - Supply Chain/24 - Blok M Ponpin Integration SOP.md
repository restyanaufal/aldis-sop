---
nomor: 24
kategori: Supply Chain
pic: Manager Outlet Blok M, Leader Ponpin
frekuensi: Setiap hari operasional
waktu_pengerjaan: Referensi operasional harian
status: Draft
versi: 1.0
terakhir_diperbarui: 2026-06-13
---

# SOP Integrasi Operasional Blok M & Pondok Pinang

> Dokumen pendukung: [[ops-flow-blokm-ponpin]] · [[SOP-OPS-03 - Operasional Dapur]] · [[19 - Inventory Usage Report]]

## Tujuan
Memastikan koordinasi antara outlet **Blok M** (titik jual) dan **Pondok Pinang / Ponpin** (dapur sentral) berjalan lancar — stok tidak pernah habis, pengiriman tepat waktu, dan bantuan crew tersedia saat demand melonjak.

## Ruang Lingkup
- Outlet Blok M: operasional penjualan, monitoring stok & antrian
- Dapur Ponpin: produksi, prep, dan pengiriman ke Blok M
- Berlaku setiap hari operasional, termasuk weekend

---

## Bagian 1 — Peran & Tanggung Jawab

| PIC | Tanggung Jawab |
|-----|----------------|
| **Manager Outlet Blok M** | Monitor stok, antrian, dan pax · Putuskan kapan order ke Ponpin · Tidak boleh tunggu habis baru order |
| **Leader Ponpin** | Jaga buffer siaga · Terima order Blok M · Pastikan pengiriman sesuai jadwal |
| **Driver / Kurir** | Antar barang tepat waktu sesuai ritme pengiriman · Jaga kondisi bahan selama perjalanan |

---

## Bagian 2 — Ritme Pengiriman Harian

### Jadwal

| Ritme | Kendaraan | Jam | Muatan |
|-------|-----------|-----|--------|
| **Pagi (Terjadwal)** | Mobil | 10.00 berangkat dari Ponpin | Roti, mayo, BBQ sauce, box & plastik, patty frozen, sosis frozen, sayur prep |
| **Siang (By Order)** | Motor | Saat ada order via WA | Patty matang, sosis matang, sayur prep, barang ketinggalan |
| **Sore (By Order)** | Motor | Saat ada order via WA | Patty matang, sosis matang, sayur prep, barang ketinggalan |

> Motor dimodifikasi untuk kapasitas bawa sayur kemasan + produk matang.

### Lead Time

| Kendaraan | Kondisi | Lead Time |
|-----------|---------|-----------|
| Mobil | Lancar | ~1 jam 10 menit |
| Mobil | Macet | ~2 jam 20 menit |
| Motor | Lancar | ~20 menit |
| Motor | Macet | ~30 menit |

> **Penting:** Lead time motor dihitung dari saat order diterima Ponpin. Jika buffer siaga ready, lead time bisa lebih pendek karena tidak perlu prep dari nol.

### Cut-off & Siklus Sayur (D+1)

| Hari | Aktivitas |
|------|-----------|
| H, maks jam 22.00 | Order sayur dari Ponpin ke supplier |
| H+1 pagi | Sayur diproses & di-prep di Ponpin |
| H+1 siang | Sayur siap dikirim ke Blok M bersama pengiriman mobil jam 10.00 |

> Ponpin wajib maintain buffer sayur 1 hari untuk antisipasi keterlambatan supplier.

---

## Bagian 3 — Buffer Siaga

### Buffer Minimum Ponpin *(dijaga s/d jam 14.00)*

| Bahan | Minimum | Catatan |
|-------|---------|---------|
| Patty matang | **40 pcs** | Di-maintain terus |
| Lettuce prep | **2 box** | Di-maintain terus |
| Kyuri prep | **1 box** | Di-maintain terus |
| Sosis | — | Tidak di-buffer — prep cepat, dibuat saat ada order |

> Setelah jam 14.00: buffer tidak digaransi. Lead time bertambah ~45–60 menit untuk prep dari nol.

### Buffer Minimum Blok M *(di outlet — wajib maintain)*

| Bahan | Minimum | Tindakan jika di bawah minimum |
|-------|---------|-------------------------------|
| Patty matang | **40 pcs** | Langsung order ke Ponpin via WA |
| Lettuce prep | **2 box** | Langsung order ke Ponpin via WA |
| Kyuri prep | **1 box** | Langsung order ke Ponpin via WA |
| Sosis | Setengah stok harian | Order ke Ponpin via WA |

> **Prinsip:** Order sebelum habis, bukan setelah habis.

---

## Bagian 4 — Trigger Order & Permintaan Bantuan

### 4.1 Trigger Restock Reguler

Manager Outlet Blok M **wajib segera order** ke Ponpin jika salah satu kondisi ini terpenuhi:

| Kondisi | Tindakan |
|---------|----------|
| Sayuran (lettuce/kyuri) sisa **setengah box** | Order sayur prep ke Ponpin via WA |
| Patty di outlet ≤ **40 pcs** | Order patty matang ke Ponpin via WA |
| Sosis di outlet ≤ **setengah stok harian** | Order sosis ke Ponpin via WA |

### 4.2 Trigger Permintaan Bantuan Crew / Support

Jika salah satu kondisi di bawah terpenuhi, Manager Outlet **segera hubungi Ponpin** untuk minta support crew atau percepatan pengiriman:

| # | Kondisi | Level |
|---|---------|-------|
| 1 | **Struk antrian > 20** | ⚠️ Siaga — persiapkan pengiriman motor berikutnya |
| 2 | **Antrian tunggu > 1 jam** | 🔴 Kritis — minta percepatan produksi + kirim motor segera |
| 3 | **Pax di outlet ≥ 50 orang** | 🔴 Kritis — minta support crew tambahan dari Ponpin |

> Jika kondisi Level Kritis, Ponpin prioritaskan pengiriman ke Blok M di atas tugas lain.

### 4.3 Format Order via WA

Tidak ada format baku, namun **wajib menyebut informasi lengkap:**

```
CONTOH — ORDER REGULER
"Ponpin, minta kirim:
- Patty matang 30 pcs
- Lettuce 1 box
- Kyuri 1 box
Kirim motor ya, thanks"

CONTOH — ORDER URGENT
"URGENT — antrian udah 1 jam lebih.
Butuh:
- Patty matang 50 pcs ASAP
- Lettuce 2 box
Tolong prioritas, kirim motor sekarang"
```

**Minimum info yang harus ada:** jenis barang + jumlah + urgensi (normal/urgent).

---

## Bagian 5 — Shift Weekend

> Penghitungan final masih dalam proses. Template ini diisi setelah trial 1–2 minggu.

| Item | Weekday | Weekend |
|------|---------|---------|
| Jam operasional | 10.00–21.00 | 10.00–21.00 |
| Crew standar | 4–5 orang | 4–5 orang |
| Tambahan crew | — | Disesuaikan load (TBD) |
| Trigger tambah crew | — | TBD setelah trial |

> **Prinsip:** Crew long shift weekend hanya diaktifkan sesuai demand aktual — tidak otomatis setiap weekend.

---

## Bagian 6 — Prosedur Eskalasi

Jika terjadi masalah yang tidak bisa diselesaikan antara Blok M dan Ponpin:

| Situasi | Eskalasi |
|---------|----------|
| Ponpin tidak bisa fulfill order dalam lead time | Manager Blok M lapor ke Owner/GM langsung |
| Kendaraan pengiriman bermasalah | Leader Ponpin koordinasi alternatif — info ke Manager Blok M |
| Stok Ponpin habis (force majeure) | Leader Ponpin segera lapor Owner/GM + cari alternatif suplai darurat |
| Antrian tidak terkendali > 2 jam | Manager Blok M lapor Owner/GM, pertimbangkan batasi order sementara |

---

## Bagian 7 — Checklist Harian Koordinasi

### Pagi *(sebelum mobil berangkat — Ponpin)*
- [ ] Buffer siaga ready: patty 40 pcs, lettuce 2 box, kyuri 1 box
- [ ] Muatan mobil pagi sesuai kebutuhan Blok M
- [ ] Driver sudah siap jam 10.00

### Pagi *(saat menerima pengiriman — Blok M)*
- [ ] Cek muatan sesuai yang dipesan
- [ ] Cek kondisi bahan (suhu, freshness)
- [ ] Update stok outlet di laporan harian

### Siang & Sore *(Blok M — monitor terus)*
- [ ] Cek level stok setiap 2 jam
- [ ] Cek jumlah antrian & pax aktif
- [ ] Order ke Ponpin segera jika trigger tercapai

---

## Catatan / Versi
- v1.0 (2026-06-13): Dibuat berdasarkan dokumen ops-flow-blokm-ponpin + input operasional langsung
- Weekend long shift (Bagian 5) masih TBD — akan diupdate setelah trial
