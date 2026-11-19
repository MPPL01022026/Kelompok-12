# 08 - Rancangan Tampilan (WBS 4.3)

Penanggung jawab: Siti Najri Apriyanti | Status: draf, posisi 31 Oktober 2026

## 1. Pilihan Bentuk dan Rekomendasi

| Pilihan | Kelebihan | Kekurangan | Penilaian |
|---|---|---|---|
| Halaman web satu layar, dibuka di HP | Tanpa instal, gratis, mudah diubah | Perlu internet untuk memuat pertama kali [ISI] | **Direkomendasikan** |
| Aplikasi Android | Bisa dipakai tanpa internet | Perlu instal dan lebih lama dibuat | Terlalu besar untuk waktu yang ada |
| Pesan WhatsApp berformat | Sudah dikenal | Pesanan tidak terurut, tidak ada ringkasan | Tidak menyelesaikan masalah |

Alasan rekomendasi: Kak Linda memakai HP, belum memahami aplikasi, dan butuh cara pesan yang mudah. Rekomendasi ini perlu disetujui Kak Linda saat demo `[KONFIRMASI]`.

## 2. Prinsip Tampilan

- Satu layar satu tugas, tombol besar, tulisan jelas.
- Isian sedikit: nama, produk, jumlah, waktu ambil.
- Bahasa sehari-hari (Tambah pesanan, Selesai).
- Warna hangat sesuai identitas proyek (emas minyak, cokelat, merah cabai).

## 3. Layar yang Direncanakan

**Layar 1 - Catat Pesanan** (sudah ada di [prototipe v0.1](../prototipe/catat-pesanan.html))

```text
+------------------------------+
| Catat Pesanan                |
| Nama pelanggan  [__________] |
| Produk [Tahu bakso v] Jml [2]|
| Harga satuan    [______] Rp  |
| Waktu ambil     [__________] |
| Catatan         [__________] |
| [      TAMBAH PESANAN      ] |
+------------------------------+
```

**Layar 2 - Daftar Pesanan dan Ringkasan**

```text
+------------------------------+
| Yang harus dibuat            |
| [Tahu bakso: 12] [Tempe: 8]  |
| Daftar pesanan               |
| Bu Rina - 2 tahu - 10.30 Baru|
|                [Proses][Hapus]|
+------------------------------+
```

**Layar 3 - Penjualan dan Stok** (tahap berikutnya, F5 dan F6)

```text
+------------------------------+
| Penjualan hari ini: Rp ...   |
| Stok bahan: [tanda hampir    |
| habis per produk]            |
+------------------------------+
```

## 4. Keterkaitan dengan Kebutuhan

| Layar | Kebutuhan |
|---|---|
| 1 | F1, F4 |
| 2 | F2, F3 |
| 3 | F5, F6 |
| Halaman pemesanan pelanggan | F7, dikerjakan setelah layar 1-2 |

Kembali ke [README](../README.md).
