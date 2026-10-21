# 05 - Pemahaman Git dan GitHub

**Git** adalah alat untuk mencatat perubahan file. **GitHub** adalah tempat menyimpan repositori Git secara daring supaya tim bisa bekerja bersama.

## 1. Istilah Penting

| Istilah | Arti singkat |
|---|---|
| Repository (repo) | Folder proyek beserta riwayat perubahannya |
| Commit | Satu catatan perubahan, disertai pesan |
| Branch | Cabang kerja terpisah dari cabang utama |
| main | Cabang utama yang isinya dianggap rapi |
| Push | Mengirim commit dari komputer ke GitHub |
| Pull | Mengambil perubahan terbaru dari GitHub |
| Clone | Menyalin repositori dari GitHub ke komputer |
| Pull Request (PR) | Permintaan agar perubahan di sebuah branch digabung ke main |
| Merge | Menggabungkan dua branch |
| Issue | Catatan tugas atau masalah di GitHub |
| Collaborator | Orang yang diberi izin ikut mengubah repositori |

## 2. Perintah Dasar

| Perintah | Fungsi |
|---|---|
| `git clone <alamat-repo>` | Menyalin repositori |
| `git status` | Melihat file yang berubah |
| `git switch -c <nama-branch>` | Membuat dan pindah ke branch baru |
| `git add <file>` | Menandai file untuk di-commit |
| `git commit -m "pesan"` | Menyimpan perubahan |
| `git pull origin main` | Mengambil pembaruan dari main |
| `git push origin <nama-branch>` | Mengirim branch ke GitHub |

## 3. Alur Kerja Tim

1. Ambil pembaruan: `git pull origin main`.
2. Buat branch sesuai tugas, contoh `wbs-fitri`.
3. Kerjakan file, lalu `add` dan `commit`.
4. `push` branch ke GitHub.
5. Buka Pull Request ke main.
6. Satu anggota lain memeriksa, lalu PR digabung.
7. Hapus branch yang sudah selesai.

## 4. Aturan Kerja

- Tidak mengedit langsung di main.
- Satu branch untuk satu tugas.
- Pesan commit singkat dan jelas, contoh: `docs: lengkapi stakeholder register`.
- Setiap PR diperiksa minimal satu anggota lain.
- Tugas dicatat di Issues dan diberi kode WBS, contoh `[2.1] Susun WBS`.
- Tidak mengunggah data pribadi pelanggan atau Kak Linda tanpa izin.
- Kalau ada konflik, selesaikan bersama lewat grup, jangan saling menimpa.

## 5. Mengundang Collaborator

1. Buka repositori di GitHub, pilih **Settings**.
2. Pilih **Collaborators** (di beberapa tampilan: **Collaborators and teams**).
3. Klik **Add people**, lalu masukkan username GitHub atau email anggota.
4. Anggota menerima undangan lewat email atau notifikasi GitHub, lalu menerimanya.
5. Tambahkan juga dosen (Cut Alna) bila diminta, dengan username yang diberikan dosen. [ISI]

## 6. Mengunggah Repositori

**Cara lewat terminal** (dilakukan satu anggota, misalnya ketua):

```bash
cd nama-folder-repositori
git init
git add .
git commit -m "docs: dokumen awal proyek"
git branch -M main
git remote add origin https://github.com/<username>/<nama-repo>.git
git push -u origin main
```

**Cara lewat web:** buat repositori baru di GitHub, pilih **Add file > Upload files**, seret seluruh isi folder (termasuk `docs/` dan `assets/`), lalu **Commit changes**.

Setelah itu anggota lain menjalankan `git clone` dan mulai bekerja dengan alur di bagian 3.

Kembali ke [README](../README.md).
