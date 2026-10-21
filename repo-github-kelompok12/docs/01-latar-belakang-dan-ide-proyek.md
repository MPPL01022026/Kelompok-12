# 01 - Latar Belakang dan Ide Proyek

**Proyek:** Pengembangan Digital Twin UMKM Bakso Goreng Kak Linda
**Mata kuliah:** Manajemen Proyek Perangkat Lunak
**Program studi:** Informatika, Universitas Samudra
**Dosen:** Cut Alna
**Kelompok:** 12

> Status: tahap perencanaan. Semua yang tertulis sebagai solusi masih **direncanakan**, belum dibuat.
> Tanda `[ISI ...]` berarti data belum ada dan akan dilengkapi setelah wawancara lanjutan.

---

## 1. Latar Belakang

Kak Linda menjalankan usaha kecil yang menjual gorengan berbahan dasar bakso. Produk yang dijual saat ini ada empat: **tahu bakso, tempe, sosis, dan bakso goreng**.

Dari wawancara awal, pesanan masuk secara **langsung**, lalu pencatatan stok, penjualan, dan keuangan dilakukan di **buku**. Kesulitan yang dirasakan Kak Linda adalah **pesanan sering lupa**.

Cara kerja seperti ini wajar untuk usaha yang masih kecil. Namun, ketika pesanan hanya masuk secara langsung dan bergantung pada ingatan serta catatan buku, ada kemungkinan pesanan terlewat dan data usaha sulit dilihat secara utuh. Kondisi inilah yang menjadi titik awal proyek ini.

Kelompok kami melihat usaha Kak Linda sebagai kasus yang cocok untuk tugas manajemen proyek perangkat lunak, karena ada masalah nyata, ruang lingkupnya masih kecil, dan pemilik usahanya bisa diwawancarai langsung.

Judul proyek memakai istilah *digital twin*. Dalam proyek ini, istilah tersebut kami artikan secara sederhana sebagai **gambaran digital dari usaha Kak Linda** (pesanan, stok, dan penjualan) yang mengikuti kondisi usaha sebenarnya. Pengertian ini masih perlu dikonfirmasi ke dosen. `[KONFIRMASI dosen]`

---

## 2. Hasil Wawancara dan Observasi

| Aspek | Hasil | Keterangan |
|---|---|---|
| Narasumber | Kak Linda (pemilik usaha) | |
| Tanggal wawancara | [ISI tanggal] | |
| Produk yang dijual | Tahu bakso, tempe, sosis, bakso | Sesuai data dari kelompok |
| Cara pesanan masuk | Langsung | Detail (lisan/tatap muka/titip) [ISI] |
| Cara mencatat stok | Buku | Format catatan [ISI] |
| Cara mencatat penjualan | Buku | Frekuensi pencatatan [ISI] |
| Cara mencatat keuangan | Buku | Pemisahan uang usaha dan pribadi [ISI] |
| Kesulitan utama | Pesanan lupa | Seberapa sering dan akibatnya [ISI] |
| Perkiraan penjualan per hari | [ISI] | |
| Waktu ramai / sepi | [ISI] | |
| Cara menentukan jumlah produksi | [ISI] | |
| Perangkat yang dipakai (HP, internet) | [ISI] | |
| Harapan Kak Linda terhadap sistem | [ISI] | |

**Pertanyaan lanjutan untuk wawancara berikutnya:**

1. Berapa kali dalam seminggu pesanan terlupa, dan apa yang terjadi saat itu (pelanggan kecewa, produk tidak dibuat, dan sebagainya)?
2. Siapa saja yang membantu usaha ini, dan apakah mereka ikut menerima pesanan?
3. Bagaimana Kak Linda tahu stok bahan hampir habis?
4. Apakah ada pelanggan tetap atau pesanan dalam jumlah besar (acara, titipan warung)?
5. Apakah Kak Linda sudah memakai WhatsApp atau media sosial untuk usahanya?
6. Bagian mana dari usaha yang paling ingin dibantu lebih dulu?

---

## 3. Identifikasi Masalah

| Kode | Masalah | Dasar | Status data |
|---|---|---|---|
| M1 | Pesanan sering lupa | Disampaikan langsung oleh Kak Linda | Fakta wawancara |
| M2 | Pesanan masuk secara langsung, sehingga belum ada catatan pesanan yang jelas sejak awal | Dari cara pesanan masuk | Perlu dikonfirmasi |
| M3 | Stok, penjualan, dan keuangan dicatat di buku, sehingga sulit dilihat ringkasannya | Dari cara pencatatan | Perlu dikonfirmasi |
| M4 | [ISI masalah lain dari wawancara lanjutan] | | |

M1 adalah satu-satunya masalah yang sudah disebut langsung oleh narasumber. M2 dan M3 adalah dugaan kelompok dari cara kerja yang diceritakan, jadi perlu dicek lagi ke Kak Linda.

### Rumusan Masalah

1. Bagaimana mengurangi pesanan yang terlupa pada usaha Kak Linda?
2. Bagaimana pesanan, stok, dan penjualan bisa dicatat dan dilihat dalam satu gambaran digital yang mengikuti kondisi usaha?
3. Bagaimana merencanakan proyek perangkat lunaknya agar sesuai dengan kemampuan usaha dan waktu kelompok?

---

## 4. Alternatif Ide

Ide awal kelompok adalah **website pemesanan**. Sebelum memutuskan, kami membandingkannya dengan beberapa alternatif lain.

| Alternatif | Gambaran singkat | Menjawab M1 (pesanan lupa) | Menjawab M2-M3 (catatan) | Kecocokan dengan judul | Perkiraan kerumitan |
|---|---|---|---|---|---|
| A. Website pemesanan | Pelanggan memesan lewat website | Ya, pesanan tercatat otomatis | Sebagian | Kurang | Sedang |
| B. Aplikasi pencatat pesanan dan stok | Kak Linda mencatat pesanan dan stok lewat aplikasi | Ya | Ya | Cukup | Sedang |
| C. Dashboard pemantauan usaha | Menampilkan ringkasan penjualan dan stok | Tidak langsung | Ya | Cukup | Sedang |
| D. Model digital usaha (digital twin sederhana) | Gabungan pesanan, stok, dan penjualan dalam satu model digital; website pemesanan menjadi salah satu jalur masuk pesanan | Ya | Ya | Sesuai | Lebih besar, perlu dibatasi |

*Penilaian di atas adalah pendapat awal kelompok dan belum diuji. Kolom "kerumitan" akan dipertajam di Analisis Titik Fungsi.*

### Ide yang Dipilih

Kelompok memilih **alternatif D**, tetapi dengan ruang lingkup yang **dibatasi** pada tahap awal: pesanan, stok, dan penjualan empat produk Kak Linda. Website pemesanan tidak dibuang. Ia direncanakan menjadi **salah satu bagian** dari model digital tersebut, yaitu tempat pesanan masuk dan tercatat.

Alasannya:

- sesuai dengan judul proyek,
- langsung menjawab masalah utama (pesanan lupa),
- tidak menyuruh Kak Linda meninggalkan cara kerjanya sekaligus, karena bisa dikembangkan bertahap.

Keputusan ini masih bisa berubah setelah wawancara lanjutan dan masukan dosen. `[KONFIRMASI kelompok dan dosen]`

---

## 5. Tujuan

**Tujuan umum**
Merencanakan pengembangan digital twin sederhana untuk usaha bakso goreng Kak Linda agar pesanan, stok, dan penjualan lebih tertata.

**Tujuan khusus**

1. Mengidentifikasi kebutuhan Kak Linda lewat wawancara dan observasi.
2. Menyusun dokumen perencanaan proyek: Project Charter, Stakeholder Register, dan WBS.
3. Menentukan ruang lingkup yang realistis untuk empat produk yang dijual.
4. Menyiapkan cara kerja tim lewat Git dan GitHub.

---

## 6. Manfaat

| Pihak | Manfaat yang diharapkan |
|---|---|
| Kak Linda (pemilik usaha) | Pesanan lebih jarang terlupa dan data usaha lebih mudah dilihat |
| Kelompok 12 | Pengalaman menyusun perencanaan proyek perangkat lunak dari kasus nyata |
| Dosen dan program studi | Contoh penerapan manajemen proyek pada UMKM sekitar kampus |

---

## 7. Dokumen Berikutnya

Dari latar belakang dan ide di atas, perencanaan dilanjutkan ke:

1. [Project Charter](02-project-charter.md)
2. [Stakeholder Register](03-stakeholder-register.md)
3. [WBS](04-wbs.md)
4. [Pemahaman Git dan GitHub](05-git-dan-github.md)

Kembali ke [README](../README.md).
