# Laporan Akhir Proyek

**Pengembangan Digital Twin UMKM Bakso Goreng Kak Linda**  
Mata kuliah Manajemen Proyek Perangkat Lunak | Informatika, Universitas Samudra  
Dosen: Cut Alna Fadhilla, S.Kom., M.Sc.  
Kelompok 12: Intan Fadila (230504074), Fitri Nabila Suhendra (230504056), Chaira Syakira Lubis (230504064), Siti Najri Apriyanti (230504073)  
Posisi data: 19 November 2026

## 1. Pendahuluan

### 1.1 Latar Belakang
Kak Linda menjual tahu bakso, tempe, sosis, dan bakso goreng. Penjualan sekitar Rp 700.000 per hari dengan harga produk sekitar Rp 1.000 sampai Rp 2.000, paling ramai sore hari. Pesanan masuk langsung, penjualan dan keuangan dicatat di buku, stok dicek saat penjualan habis. Kesulitan utamanya adalah pesanan sering lupa sehingga pembeli kurang berkenan. Usaha dijalankan sendiri dan perangkat yang dipakai adalah HP.

### 1.2 Tujuan
Merencanakan digital twin sederhana, yaitu model digital usaha yang memuat pesanan, stok, dan penjualan, agar pesanan tidak lagi terlupa dan data usaha lebih tertata. Arti digital twin di proyek ini masih usulan kelompok dan belum dikonfirmasi dosen.

### 1.3 Ruang Lingkup
Empat produk saat ini. Termasuk: pencatatan pesanan, stok, penjualan, dan ringkasan. Tidak termasuk: pembayaran online, pengiriman, produk lain, aplikasi seluler, dan akuntansi lengkap. Pemesanan pelanggan lewat website diturunkan menjadi prioritas Tambahan dan tidak dikerjakan.

## 2. Perencanaan (Tahap 1 dan 2)

| Komponen | Hasil | Rujukan |
|---|---|---|
| Latar belakang dan ide | Empat alternatif dibandingkan, dipilih model digital usaha yang dibatasi | [Dokumen 01](../01-latar-belakang-dan-ide-proyek.md) |
| Project Charter | Tujuan, ruang lingkup, kriteria keberhasilan, risiko awal, tonggak | [Dokumen 02](../02-project-charter.md) |
| Stakeholder | Lima pemangku kepentingan, matriks, rencana komunikasi | [Dokumen 03](../03-stakeholder-register.md) |
| WBS | Tujuh fase, 26 aktivitas, pembagian tugas anggota | [Dokumen 04](../04-wbs.md) |
| Jadwal | Hari kerja Senin sampai Jumat, tanggal dihitung dari durasi dan dependensi | [Jadwal](../tahap-2-project-planning/jadwal-gantt.md) |
| Manday | 83,7 manday (PERT tiga titik) | [Manday](../tahap-2-project-planning/effort-manday.md) |
| Biaya | Tunai Rp 643.500 dengan cadangan 10%, total termasuk nilai setara tenaga kerja Rp 8.419.125 | [Biaya](../tahap-2-project-planning/estimasi-biaya.md) |
| Risiko | 10 risiko, 2 Tinggi (Kak Linda belum memahami aplikasi, arti digital twin belum disepakati) | [Risiko](../tahap-2-project-planning/risk-register.md) |

## 3. Pelaksanaan (Tahap 3)

Tim bekerja tanpa ketua dan berkoordinasi lewat grup WhatsApp, GitHub Issues, dan Pull Request. Rapat tatap muka dilakukan pada 21 Oktober 2026 untuk membahas pembagian tugas, dan wawancara dengan Kak Linda pada 30 September 2026.

Hasil analisis dan perancangan: [Daftar Kebutuhan](../06-daftar-kebutuhan.md) (7 kebutuhan fungsional, 5 nonfungsional), [Alur Proses](../07-alur-proses.md), dan [Rancangan Tampilan](../08-rancangan-tampilan.md). Detail pembagian tugas dan bukti ada di [Laporan Project Execution](../tahap-3-project-execution/laporan-project-execution.md).

## 4. Monitoring dan Controlling (Tahap 4)

Tiga aktivitas yang terdata (3.1, 4.1, 4.3) selesai lebih lambat 8, 5, dan 4 hari kerja dari rencana. Manday dan biaya aktual tidak dicatat sehingga perbandingannya tidak dapat dihitung. Tercatat tujuh masalah, tiga perubahan ruang lingkup, dan tujuh tindakan korektif. Detail di [Laporan Monitoring dan Controlling](../tahap-4-monitoring-controlling/laporan-monitoring-controlling.md).

## 5. Produk Akhir dan Pengujian (Tahap 5)

**Catat Pesanan v1.0** ([prototipe](../../prototipe/catat-pesanan.html)) mencakup pencatatan pesanan, daftar dan status, ringkasan yang harus dibuat, harga dan total, penjualan harian, serta stok dengan tanda hampir habis. Pengujian oleh kelompok: 20 dari 20 uji logika dan 10 dari 10 uji tampilan lulus. Uji penerimaan dengan Kak Linda belum dilakukan. Detail di [Dokumentasi dan Pengujian](dokumentasi-dan-pengujian.md).

## 6. Evaluasi Pencapaian

| Aspek | Penilaian |
|---|---|
| Tujuan umum | Tercapai sebagai rencana dan prototipe |
| Tujuan khusus 1 (kebutuhan) | Tercapai sebagian |
| Tujuan khusus 2 sampai 4 (dokumen, ruang lingkup, GitHub) | Tercapai |
| Kriteria K1 sampai K4 | Belum terbukti sepenuhnya (menunggu validasi Kak Linda dan data dampak) |

Rincian di [Evaluasi Pencapaian](evaluasi-pencapaian.md).

## 7. Lessons Learned

Tenggat resmi perlu ditanyakan di awal, realisasi waktu, manday, dan biaya perlu dicatat harian, prototipe perlu ditunjukkan ke pengguna sedini mungkin, dan struktur repositori perlu disepakati di awal. Rincian di [Lessons Learned](lessons-learned.md).

## 8. Kesimpulan dan Saran

**Kesimpulan.** Proyek menghasilkan rencana lengkap dan prototipe yang berfungsi untuk kebutuhan utama, yaitu pesanan tidak lupa. Keberhasilan di sisi pengguna belum terbukti karena prototipe belum divalidasi Kak Linda.

**Saran.** (1) Lakukan demo langsung ke Kak Linda dan catat hasilnya. (2) Lengkapi harga tepat per produk. (3) Ukur jumlah pesanan yang terlupa sebelum dan sesudah pemakaian. (4) Kerjakan pemesanan pelanggan lewat website bila diperlukan.

Kembali ke [README](../../README.md).
