---
tags: [sop, framework, perencanaan, metodologi, tegalega]
aliases: [SOP Framework Tegalega, Cara Bikin SOP Tegalega]
---

# SOP Framework & Perencanaan — Tegalega

> Dokumen ini bukan isi SOP, tapi **cara kita membuat SOP**. Baca ini sebelum mengerjakan dokumen SOP manapun.
>
> Metodologi ini diadaptasi dari SOP Framework Aldis Hotdog (`knowledge/aldis/SOP/`) — brand F&B lain di ekosistem yang sama. Struktur dan prinsipnya brand-agnostic, jadi dipakai ulang di sini apa adanya.

---

## Konteks Tegalega

Tegalega adalah brand F&B masakan Sunda (ayam goreng basah/lengkuas, paru/babat/koyor goreng, sambal dadak/bawang, ati ampela, nasi, jukut/selada air — dijual sebagai paket). Berbeda dari Aldis Hotdog, Tegalega saat ini:

- **Baru 1 titik operasi** — belum ada multi-outlet, belum ada dokumen integrasi antar-outlet
- **Belum ada sistem POS/CK terpisah** — pencatatan masih manual/sederhana
- **Tim masih kecil** — PIC di SOP ini pakai peran generik (lihat tabel di bawah), bukan struktur jabatan formal seperti Aldis (Store Leader, Manager, SCM, Finance Staff terpisah)

### Peran Generik yang Dipakai di SOP Tegalega

| Peran | Cakupan Tugas |
|-------|---------------|
| **Owner / Penanggung Jawab** | Keputusan bisnis, approval pengeluaran besar, keputusan menu & harga |
| **Kepala Dapur** | Memimpin operasional harian — dapur, kasir, kebersihan, closing (gabungan peran "Store Leader" + "Leader" di Aldis, karena skala masih 1 titik) |
| **Crew Dapur** | Masak, prep bahan, plating |
| **Crew Kasir & Pelayanan** | Terima order, kasir, serving ke customer (bisa dirangkap Crew Dapur di jam sepi) |

> Struktur ini akan diperbarui begitu Tegalega buka outlet kedua atau merekrut posisi khusus (Finance, SCM, dst.) — lihat [[Tegalega BOM & Costing]] untuk konteks bisnis & menu terkini.

---

## Masalah yang Ingin Dihindari

Banyak SOP gagal bukan karena tidak lengkap, tapi karena:

| Masalah Umum | Dampak |
|---|---|
| Terlalu panjang & akademik | Crew tidak baca, akhirnya tidak dipakai |
| Terlalu kaku & rigid | Mengganggu flow kerja di jam sibuk |
| Dibuat tanpa input lapangan | Tidak cocok dengan kondisi nyata |
| Tidak ada sistem update | SOP jadi usang, crew ikuti yang lama |
| Terlalu banyak sekaligus | Overwhelm, tidak ada yang benar-benar dijalankan |

**Prinsip utama Tegalega:** SOP harus **membantu** crew kerja lebih cepat dan konsisten — bukan menambah beban administrasi. Karena tim masih kecil, jangan buat proses yang butuh lebih banyak orang daripada yang benar-benar ada.

---

## 3 Prinsip Dasar

### 1. Field-First
> SOP ditulis *untuk* orang di lapangan, bukan untuk manajemen.

- Bahasa: Indonesia sederhana, tidak perlu formal
- Crew harus bisa baca & pahami dalam **≤ 2 menit**
- Jika butuh lebih dari 2 menit untuk dipahami → tulis ulang

### 2. Visual > Teks
> Checklist dan tabel lebih cepat dipahami daripada paragraf.

- Gunakan **checklist** untuk tugas berurutan
- Gunakan **tabel** untuk perbandingan atau data
- Gunakan **poin pendek** — maks 1 baris per poin
- Hindari paragraf panjang

### 3. Minimal Viable SOP
> Mulai dari yang paling penting, bukan yang paling lengkap.

- SOP yang **dijalankan 80%** jauh lebih baik dari SOP sempurna yang tidak dipakai
- Mulai simpel → test di lapangan → tambahkan detail berdasarkan feedback nyata
- Jangan tunggu sempurna untuk mulai — apalagi di tahap awal seperti sekarang

---

## Format Standar Setiap SOP

Semua SOP Tegalega menggunakan struktur yang sama:

```
---
nomor: [nomor SOP]
kategori: [Operasional Toko / Dapur & Produk / Supply Chain / Penjualan / Keuangan]
pic: [siapa yang bertanggung jawab]
frekuensi: [Harian / Setiap Shift / Mingguan / Per Transaksi]
waktu_pengerjaan: [estimasi menit]
status: [Draft / Review / Aktif]
versi: 1.0
terakhir_diperbarui: [tanggal]
---

# [Nama SOP]

## Tujuan
[1 kalimat — kenapa SOP ini ada]

## Kapan Digunakan
[Kondisi / trigger kapan SOP ini dijalankan]

## Yang Dibutuhkan
[Alat, form, bahan yang perlu disiapkan sebelum mulai]

## Langkah-Langkah
- [ ] Langkah 1
- [ ] Langkah 2
- [ ] Langkah 3
...

## Standar Kelulusan
[Bagaimana crew tahu bahwa tugas ini sudah selesai dengan benar]

## Jika Ada Masalah
[Apa yang dilakukan jika ada kondisi tidak normal]

## Catatan / Versi
[Log perubahan singkat]
```

---

## Aturan Penulisan (Do's & Don'ts)

### ✅ DO
- Tulis dalam urutan kronologis (apa yang dilakukan pertama, kedua, dst.)
- Sertakan **angka spesifik** (suhu, waktu, jumlah) bukan "secukupnya"
- Tambahkan **contoh konkret** untuk hal yang ambigu
- Sebutkan siapa **PIC** dengan jelas
- Tambahkan **"Jika Ada Masalah"** untuk skenario yang sering terjadi

### ❌ DON'T
- Jangan tulis "sesuai kebutuhan" atau "sesuai situasi" tanpa parameter
- Jangan campurkan 2 SOP berbeda dalam 1 dokumen
- Jangan gunakan istilah teknis tanpa penjelasan
- Jangan buat SOP lebih dari **1 halaman A4** untuk tugas harian
- Jangan finalize SOP tanpa pernah ditest di lapangan
- Jangan pakai struktur multi-outlet (rotasi antar-outlet, integrasi gudang besar-kecil, dsb.) — belum relevan di tahap ini

---

## Prioritas Pengerjaan

SOP dikerjakan berdasarkan **dampak langsung ke kualitas produk & keselamatan** — bukan urutan nomor. Untuk Tegalega, ini lebih kritis karena masakan yang digoreng (ayam, paru, babat, koyor) rentan food safety kalau salah handle.

### Fase 1 — Kritis (Kerjakan Pertama)
*Langsung berdampak ke food safety, konsistensi rasa, dan keselamatan (minyak panas, gorengan)*

| SOP | Alasan Prioritas |
|-----|-------------------|
| Food Safety Checklist | Keselamatan — ayam & jeroan paling rawan kontaminasi |
| Opening Checklist Report | Fondasi operasional harian |
| Standard Recipe Book | Konsistensi rasa = identitas brand Sunda |
| Cooking Time Standard | Ayam & jeroan butuh waktu masak presisi |
| Emergency Response | Risiko kebakaran/minyak panas tinggi di dapur gorengan |
| Store Cleaning Checklist | Hygiene — wajib sebelum buka |

### Fase 2 — Operasional Harian
*Memastikan crew bisa kerja efisien dan konsisten setiap hari*

| SOP | Alasan |
|-----|--------|
| Grooming Standardization | Brand image ke customer |
| Greeting Standard | Customer experience langsung terasa |
| Menu Availability Checklist | Mencegah crew jual paket yang bahannya habis |
| Plating Guide | Konsistensi visual paket nasi |
| Next Day Preparation List | Mengurangi kekacauan pagi hari |

### Fase 3 — Supply Chain & Inventory
*Memastikan stok tidak pernah kosong dan tidak ada pemborosan*

| SOP | Alasan |
|-----|--------|
| FIFO Monitoring Sheet | Mencegah bahan mentah (ayam/jeroan) kadaluarsa terpakai |
| Delivery Order | Kelancaran belanja bahan baku |
| Inventory Usage Report | Data untuk belanja berikutnya |

### Fase 4 — Reporting & Analitik
*Data untuk evaluasi dan pengambilan keputusan*

| SOP | Alasan |
|-----|--------|
| Daily Sales Report | Input harian untuk decision |
| Waste Analysis Report | Identifikasi pemborosan |
| Quality Control Form | Evaluasi sistematis kualitas |
| Petty Cash | Kontrol pengeluaran harian |

### Fase 5 — Strategic & Customer Insight
*Data jangka panjang untuk growth*

| SOP | Alasan |
|-----|--------|
| Customer Feedback Form | Data kepuasan |
| Store Performance History | Baseline performa sebelum ekspansi |
| Upselling Product | Meningkatkan APC |
| Sales Summary Report | Rekap performa periodik |

---

## Alur Pembuatan SOP (Per Dokumen)

```
1. DRAFT
   └─ Tulis berdasarkan cara kerja yang sudah berjalan di lapangan
   └─ PIC: Owner + input dari Kepala Dapur

2. REVIEW LAPANGAN
   └─ Berikan draft ke crew yang paling berpengalaman
   └─ Minta mereka baca dan coba jalankan
   └─ Catat semua kebingungan dan pertanyaan mereka

3. REVISI
   └─ Update berdasarkan feedback lapangan
   └─ Jika masih ada yang bingung → tulis ulang, bukan tambahkan keterangan

4. UJI COBA (1–2 minggu)
   └─ Jalankan SOP di operasional harian
   └─ Pantau apakah ada hambatan di jam sibuk
   └─ Crew boleh kasih feedback langsung ke Kepala Dapur

5. FINALIZE & AKTIFKAN
   └─ Update status dari "Draft" → "Aktif"
   └─ Simpan di lokasi yang mudah diakses crew (printed / WhatsApp group)
   └─ Lakukan briefing singkat (maks 10 menit) ke seluruh tim

6. REVIEW BERKALA
   └─ Evaluasi setiap 3 bulan atau saat ada perubahan menu/proses
```

---

## Skala Kompleksitas SOP

| Tipe | Frekuensi | Kompleksitas | Format |
|------|-----------|-------------|--------|
| **Tugas Harian Rutin** | Setiap hari / shift | Rendah | Checklist singkat, maks 10 poin |
| **Standar Produk** | Per produksi | Sedang | Tabel bahan + langkah dengan angka spesifik |
| **Quality Control** | Per batch / harian | Sedang | Form isian + kriteria lulus/gagal |
| **Supply Chain** | Per pengiriman/belanja | Tinggi | Urutan langkah + dokumen pendukung |
| **Pelaporan** | Harian/Mingguan | Rendah | Template isian + deadline |

---

## Cara Menentukan Apakah SOP Sudah Cukup Baik

Sebelum finalize, jawab 5 pertanyaan ini:

- [ ] **Crew baru bisa langsung jalankan** tanpa perlu tanya-tanya ke senior?
- [ ] **Tidak ada langkah yang ambigu** — semua ada angka, waktu, atau kriteria jelas?
- [ ] **Sudah ditest di lapangan** minimal 1 minggu?
- [ ] **Tidak menambah waktu kerja** lebih dari 10% dibanding cara lama?
- [ ] **PIC sudah tahu** bahwa mereka bertanggung jawab atas SOP ini?

Jika ada yang belum ✅ → jangan finalize dulu.

---

## Sistem Update SOP

SOP bukan batu. Perlu diupdate jika:

| Trigger Update | Contoh |
|---|---|
| Ada perubahan menu / resep | Paket baru, resep berubah, harga bahan berubah signifikan |
| Ada perubahan supplier / bahan | Ganti supplier ayam/paru/koyor, bahan pengganti |
| Sering terjadi kesalahan yang sama | Crew salah step yang sama berulang kali |
| Audit 3 bulanan | Review rutin scheduled |
| Feedback dari customer | Keluhan berulang yang berkaitan dengan proses |
| Buka outlet kedua | Struktur peran & SOP supply chain perlu di-upgrade ke model multi-outlet |

**Cara update:**
1. Jangan hapus versi lama — tambahkan di bagian "Catatan / Versi"
2. Update tanggal `terakhir_diperbarui` di frontmatter
3. Naikkan nomor versi (1.0 → 1.1 → 2.0)
4. Brief ulang tim jika ada perubahan signifikan

---

## Distribusi SOP ke Tim

| Format | Digunakan untuk | Cara Distribusi |
|--------|-----------------|----------------|
| **Printed Laminated** | Checklist harian di dapur / kasir | Print A4, laminate, tempel di area kerja |
| **WhatsApp Group** | Update SOP baru, reminder | Kirim PDF ke grup tim |
| **Obsidian Vault** | Master dokumen, reference | File ini (`knowledge/tegalega/SOP/`) |

---

## Tautan Terkait

- [[SOP Index]] — Daftar semua dokumen SOP Tegalega + status
- [[Tegalega BOM & Costing]] — Menu, resep, komposisi biaya, dan konteks bisnis Tegalega
