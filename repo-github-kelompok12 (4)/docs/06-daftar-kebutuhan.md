# 06 - Daftar Kebutuhan (WBS 3.1)

Penanggung jawab: Chaira Syakira Lubis | Status: draf, posisi 31 Oktober 2026

Daftar ini disusun dari [wawancara dengan Kak Linda](01-latar-belakang-dan-ide-proyek.md) pada 30 September 2026 dan rapat kelompok 21 Oktober 2026. Hal yang belum diketahui ditandai `[ISI]` atau `[KONFIRMASI]`.

## 1. Dasar Kebutuhan

| Fakta dari wawancara | Artinya bagi kebutuhan |
|---|---|
| Pesanan masuk langsung, pesanan sering lupa, akibatnya pembeli kurang berkenan | Pesanan harus tercatat sejak diterima |
| Pencatatan stok, penjualan, dan keuangan memakai buku | Catatan harian perlu lebih mudah dilihat ringkasannya |
| Stok dicek ketika penjualan sudah habis | Stok perlu dipantau lebih awal |
| Harga produk sekitar Rp 1.000 sampai Rp 2.000, penjualan sekitar Rp 700.000 per hari | Perkiraan kasar 350 sampai 700 buah per hari (700.000 dibagi 2.000 atau 1.000). Perlu dikonfirmasi |
| Tidak ada pembantu usaha | Satu pengguna utama, yaitu Kak Linda |
| Perangkat yang dipakai: HP | Aplikasi harus nyaman dipakai di HP |
| Kak Linda belum memahami aplikasi dan mengikuti usulan kelompok | Tampilan dan alur harus sangat sederhana |
| Yang diinginkan: pemesanan mudah dan tidak lupa | Prioritas utama proyek |

## 2. Kebutuhan Fungsional

| Kode | Kebutuhan | Prioritas | Dasar |
|---|---|---|---|
| F1 | Mencatat pesanan: nama pelanggan, produk, jumlah, waktu ambil, catatan | Wajib | Pesanan lupa |
| F2 | Menampilkan daftar pesanan berurutan waktu ambil dengan status Baru, Diproses, Selesai | Wajib | Pesanan lupa |
| F3 | Menampilkan ringkasan jumlah tiap produk yang harus dibuat | Wajib | Pesanan lupa, akibat pembeli kurang berkenan |
| F4 | Menyimpan harga satuan tiap produk dan menghitung total pesanan | Penting | Harga Rp 1.000 sampai Rp 2.000 |
| F5 | Mencatat penjualan harian dan menampilkan ringkasannya | Penting | Pencatatan di buku |
| F6 | Mencatat stok bahan dan memberi tanda saat hampir habis | Penting | Stok dicek saat sudah habis. [KONFIRMASI Kak Linda] |
| F7 | Pemesanan oleh pelanggan lewat halaman web sederhana | Tambahan | Harapan pemesanan mudah. Dikerjakan setelah F1-F3 |

## 3. Kebutuhan Nonfungsional

| Kode | Kebutuhan |
|---|---|
| N1 | Dapat dibuka di HP tanpa memasang aplikasi |
| N2 | Tombol besar, isian sedikit, bahasa sehari-hari |
| N3 | Tanpa biaya langganan |
| N4 | Data pelanggan hanya dipakai untuk pesanan |
| N5 | Dapat dipakai satu orang tanpa pelatihan panjang |

## 4. Batasan dan Hal yang Belum Diketahui

- Ruang lingkup tetap empat produk: tahu bakso, tempe, sosis, bakso goreng.
- Harga tepat per produk: [ISI]. Penjualan per produk: [ISI]. Jam ramai: [ISI].
- Ketersediaan internet di tempat usaha: [ISI].
- Seberapa sering pesanan lupa dalam seminggu: belum diketahui.

Lanjut ke [Alur Proses](07-alur-proses.md). Kembali ke [README](../README.md).
