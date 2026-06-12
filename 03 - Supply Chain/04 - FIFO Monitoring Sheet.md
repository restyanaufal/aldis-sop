---
nomor: 4
kategori: Supply Chain
pic: SCM & Store Leader
frekuensi: Setiap penerimaan stok baru + cek harian
waktu_pengerjaan: 5–10 menit
status: Draft
versi: 2.0
terakhir_diperbarui: 2026-06-13
---

# FIFO Monitoring Sheet

> Dokumen terkait: [[03 - Delivery Order]] · [[05 - Food Safety Checklist]] · [[19 - Inventory Usage Report]]

## Tujuan
Memastikan stok yang lebih lama masuk digunakan lebih dulu dan memverifikasi kondisi bahan saat diterima — mencegah produk kadaluarsa terpakai dan meminimalkan waste.

**FIFO = First In, First Out** — yang pertama masuk, pertama dipakai.
**FEFO = First Expired, First Out** — yang kadaluarsa lebih awal, dipakai lebih dulu (berlaku jika tanggal exp berbeda antar batch).

---

## Bagian 1 — Cold Chain Monitoring (Penerimaan dari CPNB/Supplier)

Setiap kali menerima bahan protein (patty, sosis, nugget) dari CPNB atau supplier, **wajib cek suhu** sebelum diterima.

### Standar Suhu Penerimaan

| Bahan | Suhu Maksimal Saat Terima | Tindakan Jika Melebihi |
|-------|--------------------------|----------------------|
| Patty / Beef (chilled) | ≤ 8°C | **Tolak** — jangan terima, foto, lapor SCM |
| Sosis (chilled) | ≤ 8°C | **Tolak** — jangan terima, foto, lapor SCM |
| Nugget Chicken | ≤ 8°C | **Tolak** — jangan terima, foto, lapor SCM |
| Sayuran segar | ≤ 10°C atau kondisi segar | Tolak jika sudah layu/busuk |
| Odading / Roti (dari CPNB) | Suhu ruang, tidak lembab | Tolak jika lembab atau ada bau |

> Gunakan termometer yang sudah dikalibrasi (→ [[26 - Kalibrasi & Pemeliharaan Alat]])

### Log Penerimaan + Suhu

**Outlet:** __________ | **Bulan:** __________

| Tanggal | Dari | Nama Bahan | Jumlah | Suhu Terima | Kondisi Visual | Diterima? | PIC |
|---------|------|-----------|--------|------------|---------------|----------|-----|
| | CPNB / Supplier | Patty | pcs | °C | ✅/❌ | Ya/Tidak | |
| | CPNB / Supplier | Sosis | pcs | °C | ✅/❌ | Ya/Tidak | |
| | CPNB / Supplier | Nugget | pcs | °C | ✅/❌ | Ya/Tidak | |
| | CPNB / Supplier | Sayuran | box | — | ✅/❌ | Ya/Tidak | |
| | CPNB / Supplier | Odading | pcs | — | ✅/❌ | Ya/Tidak | |

**Prosedur Penolakan Bahan:**
1. Foto kondisi bahan + termometer (jika suhu menyimpang)
2. Jangan masukkan ke chiller outlet
3. Hubungi SCM / Ponpin segera — minta penggantian
4. Catat di form ini sebagai "Ditolak" + keterangan alasan

---

## Bagian 2 — Aturan FIFO Penyimpanan

| Bahan | Cara Penyimpanan FIFO |
|-------|----------------------|
| Patty / Sosis / Nugget | Stok lama di **depan** chiller, stok baru di **belakang** |
| Odading / Bun | Stok lama di **atas / depan** rak, stok baru di **bawah / belakang** |
| Sayuran | Gunakan yang dibeli hari kemarin dulu sebelum yang baru |
| Kondimen (mayo, BBQ sauce) | Kemasan yang sudah dibuka **dihabiskan dulu** sebelum buka yang baru |

**Aturan utama:** Saat stok baru datang → **langsung atur posisinya** sebelum disimpan.

---

## Bagian 3 — Cara Penandaan Stok

Semua bahan yang masuk harus diberi label segera setelah diterima:

```
[Tanggal Terima: ____]  [Exp: ____]  [Jumlah: ____]  [PIC: ____]
```

- Gunakan stiker / selotip + spidol permanen
- Tempel di kemasan atau wadah penyimpanan
- **Bahan tanpa label = tidak boleh dipakai** sebelum diberi label

---

## Bagian 4 — Cek FIFO Harian (Saat Buka)

- [ ] Bahan paling lama tanggal terimanya ada di posisi paling mudah dijangkau (depan/atas)
- [ ] Tidak ada bahan tanpa label tanggal
- [ ] Tidak ada bahan yang sudah lewat tanggal kadaluarsa di storage
- [ ] Stok baru yang datang kemarin sudah diatur di belakang stok lama
- [ ] Kondisi chiller: suhu ≤ 4°C *(catat di log suhu [[05 - Food Safety Checklist]])*

**PIC:** __________ | **Jam:** __________ | **Tanda tangan:** __________

---

## Sheet Monitoring Bulanan

**Outlet:** __________ | **Bulan:** __________

| Tanggal Terima | Nama Produk | Jumlah Masuk | Exp Date | Sisa Awal | Terpakai Hari Ini | Sisa Akhir | PIC |
|----------------|-------------|-------------|----------|-----------|-------------------|------------|-----|
| | Patty Reguler | | | | | | |
| | Patty Medium | | | | | | |
| | Sosis | | | | | | |
| | Nugget | | | | | | |
| | Odading | | | | | | |
| | Bun | | | | | | |

---

## Standar Kelulusan
Tidak ada produk kadaluarsa yang tersimpan. Semua bahan berlabel. Stok lama di posisi depan. Suhu penerimaan bahan protein tercatat dan sesuai standar.

## Jika Ada Masalah

| Masalah | Tindakan |
|---------|----------|
| Bahan diterima di atas suhu standar | Tolak pengiriman, foto, lapor SCM, minta penggantian |
| Bahan kadaluarsa ditemukan di storage | Pisahkan, jangan gunakan, catat di Waste Report (→ [[21 - Waste Analysis Report]]), lapor Leader |
| Bahan tanpa label ditemukan | Tanyakan ke crew yang terima — jika tidak bisa dikonfirmasi, anggap meragukan |
| Stok lama terpakai setelah stok baru | Re-brief crew tentang FIFO — cek apakah penyusunan storage sudah benar |

---

## Catatan / Versi
- v1.0 (2026-06-12): Draft awal — fundamental multi-outlet
- v2.0 (2026-06-13): Tambah cold chain monitoring (suhu penerimaan), log penerimaan + prosedur penolakan bahan
