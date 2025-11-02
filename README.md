# Laporan Workflow Git - Portofolio Web
Repositori ini adalah bagian dari tugas praktikum untuk mendemonstrasikan alur kerja Git dasar pada proyek website portofolio statis.

## Deskripsi Proyek
Proyek ini merupakan bagian dari **Praktikum Pemrograman Web - Judul 2**, di mana fokus pembelajarannya adalah untuk memahami dan mengimplementasikan dasar-dasar *version control* menggunakan Git.

Website portofolio ini sendiri berfungsi sebagai objek studi kasus untuk menerapkan alur kerja Git, mulai dari inisialisasi, commit bertahap, *branching* untuk eksperimen fitur (styling), hingga *merging* kembali ke branch utama.

---

* **Nama:** Muhammad Farhan
* **NPM:** 2315061083
* **GitHub:** [@muhparhaan](https://github.com/muhparhaan)

---

## 📋 Langkah-Langkah Alur Kerja Git

Berikut adalah langkah-langkah nyata yang saya lakukan untuk mengelola proyek ini, sesuai dengan riwayat commit:

1.  **Inisialisasi Proyek**
    * Membuat repositori lokal baru (`git init`).
    * `907ec83 Initial commit`

2.  **Commit Bertahap (di Branch `main`)**
    * Saya melakukan commit secara bertahap untuk membangun website.
    * `a03a3b9 Add files via upload` (Menambahkan file-file awal proyek)
    * `c7ec372 tambah section contact` (Menyelesaikan penambahan section contact)
    * `4d612f8 perbarui section kontak saya` (Melakukan revisi pada section contact)

3.  **Membuat Branch untuk Eksperimen (`parhun`)**
    * Untuk mencoba *styling* baru (mengubah dari tema gelap ke tema terang), saya membuat branch terpisah dengan nama `parhun`.
    * `git checkout -b parhun`

4.  **Commit di Branch Eksperimen**
    * Setelah mengubah file `style.css` menjadi tema terang, saya melakukan commit di branch `parhun`.
    * `abe35a2 ubah tema menjadi terang`

5.  **Menggabungkan Branch (Merge)**
    * Setelah puas dengan hasilnya, saya kembali ke branch `main`.
    * `git checkout main`
    * Saya menggabungkan (merge) semua perubahan dari `parhun` ke `main`.
    * `git merge parhun`
    * *(Log saya menunjukkan `(HEAD -> main, origin/main, origin/HEAD, parhun)`, yang berarti merge telah berhasil dan branch `main` serta `parhun` sekarang berada di commit `abe35a2` yang sama).*

6.  **Push ke GitHub**
    * Menghubungkan repositori lokal ke GitHub dan mem-push semua riwayat commit.
    * `git remote add origin https://github.com/muhparhaan/TUGAS-AKHIR-PRAK-PW-JUDUL-2.git`
    * `git push -u origin main`

7.  **Menambah README**
    * Membuat file `README.md` ini, melakukan commit, dan men-pushnya ke GitHub.

---

## 🚀 Instalasi dan Penggunaan

Untuk melihat website ini secara lokal:

1.  **Clone repositori** ini:
    ```bash
    git clone [https://github.com/muhparhaan/TUGAS-AKHIR-PRAK-PW-JUDUL-2.git](https://github.com/muhparhaan/TUGAS-AKHIR-PRAK-PW-JUDUL-2.git)
    ```

2.  **Masuk ke direktori** proyek:
    ```bash
    cd TUGAS-AKHIR-PRAK-PW-JUDUL-2
    ```

3.  **Buka file `index.html`** di browser Anda.