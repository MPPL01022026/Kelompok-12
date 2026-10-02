# 🍢 WarungTwin

**Digital Twin Operasional Penjualan dan Stok untuk UMKM**

WarungTwin adalah replika digital operasional penjualan dan stok yang dikembangkan untuk UMKM **Bakso Goreng Kak Linda**. Sistem ini memantau, mensimulasikan, dan memprediksi penjualan serta kebutuhan stok agar pemilik usaha tidak lagi menghitung pendapatan secara manual dan stok tidak sering habis.

> Proyek Mata Kuliah Manajemen Proyek Perangkat Lunak (MPPL)
> Program Studi Informatika, Fakultas Sains dan Teknologi, Universitas Samudra, 2026

---
## 👩‍💻 Tim Pengembang

| Nama | NIM |
| --- | --- |
| Intan Fadila | 230504074 |
| Fitri Nabila Suhendra | 230504056 |
| Chaira Syakira Lubis | 230504064 |
| Siti Najri Apriyanti | 230504073 |

**Program Studi Informatika, Fakultas Sains dan Teknologi, Universitas Samudra, 2026**

## 📌 Latar Belakang

Bakso Goreng Kak Linda berlokasi di depan Universitas Samudra dan sudah berjalan sekitar 4 tahun. Usaha buka setiap hari tanpa libur mulai pukul 17.00 dengan penghasilan rata-rata sekitar Rp700.000 per hari.

Masalah yang teridentifikasi:

- Stok tahu sering habis.
- Penghasilan masih dihitung sendiri secara manual.
- Belum ada pencatatan digital.
- Belum memakai barcode maupun promosi lewat media sosial (Instagram/TikTok).

## 🎯 Tujuan

Membangun sistem *digital twin* yang memantau, mensimulasikan, dan memprediksi penjualan serta stok usaha.

**Sasaran terukur:**

1. Penjualan dan stok terpantau secara real-time.
2. Akurasi prediksi kebutuhan stok harian.
3. Sistem selesai dan diuji.

## ✨ Fitur Utama

| Fitur | Deskripsi |
| --- | --- |
| **Model operasional virtual** | Alur stok bahan (tahu, mie gulung, bakso, tempe), penjualan, dan pendapatan terlihat real-time di dashboard. |
| **Pencatatan penjualan digital** | Input lewat tombol menu produk di ponsel/tablet. Pendapatan harian dihitung otomatis, tanpa barcode. |
| **Simulasi permintaan & stok** | Contoh: jika pembeli naik 30% saat akhir pekan, pada jam berapa tahu habis dan berapa stok tambahan yang dibutuhkan? |
| **Prediksi kebutuhan stok** | Prediksi stok harian dan peringatan dini saat stok hampir habis, berdasarkan pola penjualan historis. |
| **Laporan otomatis** | Pendapatan harian/mingguan/bulanan, produk terlaris, jam ramai, dan kejadian stok habis. |

## 📦 Lingkup Proyek

**Dalam lingkup (in scope):**

- Dashboard web
- Modul pencatatan penjualan
- Modul stok
- Model simulasi permintaan
- Prediksi kebutuhan stok
- Laporan pendapatan otomatis
- Pelatihan pengguna

**Di luar lingkup (out of scope):**

- Barcode/QR produk
- Pengelolaan promosi media sosial
- Aplikasi mobile native
- Payment gateway

## 🧰 Tech Stack

> Sesuaikan dengan teknologi yang digunakan tim.

| Komponen | Teknologi |
| --- | --- |
| Frontend | _[HTML-CSS-JS]_ |
| Backend | _[Laravel (PHP)]_ |
| Database | _[MySQL]_ |
| Prediksi & Simulasi | _[PHP (Laravel)]_ |
| Hosting | _[Shared hosting atau Railway/Render]_ |

## 🚀 Instalasi

> Sesuaikan langkah berikut dengan stack yang dipakai.

```bash
# 1. Clone repositori
git clone https://github.com/<username>/warungtwin.git
cd warungtwin

# 2. Install dependensi
# contoh: npm install / composer install / pip install -r requirements.txt

# 3. Salin dan atur konfigurasi environment
cp .env.example .env

# 4. Jalankan migrasi database
# contoh: php artisan migrate / npx prisma migrate dev

# 5. Jalankan aplikasi
# contoh: npm run dev / php artisan serve / flask run
```

## 🗂️ Struktur Proyek

> Contoh struktur, sesuaikan dengan repositori.

```
warungtwin/
├── docs/               # Project Charter, Stakeholder Register, WBS, desain sistem, panduan pengguna
├── src/
│   ├── penjualan/      # Modul pencatatan penjualan
│   ├── stok/           # Modul stok
│   ├── simulasi/       # Modul simulasi permintaan & stok
│   ├── prediksi/       # Modul prediksi kebutuhan stok
│   ├── laporan/        # Modul laporan
│   └── dashboard/      # Dashboard real-time
├── tests/              # Unit, integration, dan UAT
├── .env.example
└── README.md
```

## 🗓️ Ringkasan Project Charter

| Elemen | Isi |
| --- | --- |
| **Judul** | Pengembangan WarungTwin: Digital Twin Operasional Penjualan dan Stok untuk UMKM Bakso Goreng Kak Linda |
| **Jadwal** | Sekitar 4 minggu |
| **Project Manager** | Anggota kelompok |
| **Deliverables** | Dokumen kebutuhan, desain sistem, prototipe/aplikasi web, hasil pengujian, panduan pengguna, laporan akhir |
| **Kriteria keberhasilan** | Sistem berjalan di lokasi usaha, lulus UAT, dan disetujui pemilik |

**Asumsi:** Pemilik bersedia memberi data dan akses observasi pada jam buka (mulai pukul 17.00); tersedia ponsel/tablet dan koneksi internet di lokasi jualan.

**Batasan:** Waktu satu semester, anggaran terbatas, data historis minim, dan jam operasional terbatas pada sore hingga malam hari.

**Risiko utama:**

- Data penjualan awal tidak lengkap.
- Pemilik/karyawan sulit beradaptasi dengan pencatatan digital.
- Input data terhambat saat jam ramai.
- Perubahan kebutuhan.
- Jadwal bentrok dengan kegiatan akademik.

## 👥 Stakeholder

| Stakeholder | Peran | Strategi |
| --- | --- | --- |
| Pemilik usaha | Sponsor & pengguna utama | Manage closely |
| Karyawan/pembantu jualan | Pengguna harian | Keep informed + pelatihan |
| Pelanggan | Pengguna akhir | Keep informed |
| Dosen pengampu/pembimbing | Penilai & pembimbing | Manage closely |
| Tim pengembang | Pelaksana | Manage closely |
| Pemasok (tahu dan bahan baku) | Pendukung operasional | Keep informed |
| Pedagang/kompetitor sekitar | Pihak eksternal | Monitor |

## 🧩 Work Breakdown Structure (WBS)

```
1. WarungTwin
├── 1.1 Inisiasi
│   ├── 1.1.1 Pemilihan UMKM & wawancara awal
│   ├── 1.1.2 Penyusunan Project Charter
│   └── 1.1.3 Identifikasi stakeholder (Stakeholder Register)
├── 1.2 Perencanaan
│   ├── 1.2.1 Rencana lingkup, jadwal, dan anggaran
│   ├── 1.2.2 Rencana risiko dan komunikasi
│   └── 1.2.3 Penyusunan WBS dan jadwal kerja
├── 1.3 Analisis & Desain
│   ├── 1.3.1 Observasi dan pemetaan alur penjualan dan stok
│   ├── 1.3.2 Analisis kebutuhan (fungsional & non-fungsional)
│   ├── 1.3.3 Desain model digital twin (alur, status stok, aturan simulasi)
│   ├── 1.3.4 Desain basis data
│   └── 1.3.5 Desain antarmuka (wireframe/prototipe)
├── 1.4 Pengembangan
│   ├── 1.4.1 Modul pencatatan penjualan
│   ├── 1.4.2 Dashboard penjualan dan stok real-time
│   ├── 1.4.3 Modul simulasi permintaan & stok
│   ├── 1.4.4 Modul prediksi kebutuhan stok
│   └── 1.4.5 Modul laporan
├── 1.5 Pengujian
│   ├── 1.5.1 Unit dan integration testing
│   ├── 1.5.2 User Acceptance Testing bersama pemilik dan karyawan
│   └── 1.5.3 Perbaikan bug
├── 1.6 Implementasi & Pelatihan
│   ├── 1.6.1 Deployment
│   ├── 1.6.2 Pelatihan pengguna
│   └── 1.6.3 Panduan pengguna
├── 1.7 Pemantauan & Pengendalian
│   ├── 1.7.1 Laporan progres berkala
│   └── 1.7.2 Pengelolaan perubahan dan risiko
└── 1.8 Penutupan
    ├── 1.8.1 Serah terima ke pemilik
    ├── 1.8.2 Laporan akhir dan lessons learned
    └── 1.8.3 Presentasi akhir
```
