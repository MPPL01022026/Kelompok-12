# Risk Register

Skala 1-5. Skor = probabilitas x dampak. 15 ke atas **Tinggi**, 8-14 **Sedang**, di bawah 8 **Rendah**. Nilai probabilitas dan dampak adalah penilaian awal kelompok.

| Kode | Risiko | P | D | Skor | Level | Strategi | Mitigasi | Pemilik | Pemicu |
|---|---|:-:|:-:|:-:|---|---|---|---|---|
| R1 | Data wawancara belum lengkap, kebutuhan Kak Linda salah dipahami | 3 | 4 | 12 | Sedang | Kurangi | Jadwalkan wawancara lanjutan, siapkan daftar pertanyaan, catat hasil di dokumen 01 | Chaira | Data harga per produk dan frekuensi pesanan lupa masih kosong |
| R2 | Kak Linda sulit ditemui atau waktunya terbatas | 3 | 4 | 12 | Sedang | Kurangi | Buat janji sejak awal, siapkan pertemuan singkat, cadangan lewat pesan | Intan | Janji temu batal dua kali berturut-turut |
| R3 | Kak Linda belum memahami aplikasi, hanya mengikuti usulan kelompok | 4 | 4 | 16 | Tinggi | Kurangi | Rancangan sangat sederhana, demo langsung di HP, uji coba didampingi, panduan bergambar | Siti | Kak Linda tidak bisa mencatat satu pesanan sendiri saat demo |
| R4 | Arti digital twin belum disepakati dengan dosen | 3 | 5 | 15 | Tinggi | Hindari | Konsultasi dengan Cut Alna Fadhilla, S.Kom., M.Sc., tulis definisi di Project Charter | Siti | Dosen meminta ruang lingkup berbeda dari Charter |
| R5 | Anggota hanya 4 orang, beban tiap orang berat | 4 | 3 | 12 | Sedang | Kurangi | Pembagian tugas jelas di WBS, pantau mingguan, batasi ruang lingkup | Fitri | Tugas terlambat lebih dari 2 hari kerja |
| R6 | Jadwal bentrok dengan kuliah atau ujian lain | 3 | 3 | 9 | Sedang | Kurangi | Kerjakan tugas paralel, pantau cadangan waktu menuju tenggat | Fitri | Jadwal ujian diumumkan pada rentang pengerjaan |
| R7 | Ruang lingkup berubah di tengah jalan | 3 | 4 | 12 | Sedang | Kurangi | Persetujuan tertulis ruang lingkup, catat setiap perubahan | Siti | Ada permintaan fitur baru setelah analisis kebutuhan |
| R8 | Anggota berhalangan (sakit atau urusan lain) | 2 | 4 | 8 | Sedang | Kurangi | Tugas cadangan antaranggota, semua pekerjaan disimpan di GitHub | Fitri | Anggota tidak aktif lebih dari 3 hari kerja |
| R9 | File bentrok atau hilang di GitHub | 2 | 3 | 6 | Rendah | Kurangi | Branch per tugas, Pull Request, aturan kerja di dokumen 05 | Intan | Konflik merge muncul berulang |
| R10 | Biaya tunai melebihi rencana | 2 | 2 | 4 | Rendah | Terima | Pakai layanan gratis, ada cadangan 10% | Chaira | Pengeluaran tunai melampaui total tunai rencana |

## Peta Risiko (kode risiko per sel)

| Dampak \ Probabilitas | 1 | 2 | 3 | 4 | 5 |
|---|:-:|:-:|:-:|:-:|:-:|
| 5 | - | - | R4 | - | - |
| 4 | - | R8 | R1, R2, R7 | R3 | - |
| 3 | - | R9 | R6 | R5 | - |
| 2 | - | R10 | - | - | - |
| 1 | - | - | - | - | - |

Ringkasan: 2 risiko Tinggi (R3, R4), 6 Sedang, 2 Rendah.

Kembali ke [README](../../README.md).