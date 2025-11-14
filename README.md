# Tugas Tracker - Front-End (FE)

## Penjelasan Proyek Singkat

Aplikasi Tugas Tracker adalah website yang dikembangkan untuk membantu mahasiswa mengelola beban kerja, melacak deadline tugas, dan memantau status pengerjaan tugas dari berbagai mata kuliah yang diambil. Aplikasi ini bertujuan menyediakan satu sistem terpusat untuk manajemen tugas.

## Struktur Folder (Folder Structure)

Proyek Front-End ini dibangun menggunakan React (Vite). Berikut adalah struktur direktori utama yang digunakan:

* **`src/**`: Direktori utama yang berisi semua kode sumber aplikasi React.
* **`src/components`**: Berisi komponen-komponen kecil yang dapat digunakan berulang di seluruh aplikasi (e.g., Tombol, Kartu Tugas, Header).
* **`src/pages`**: Berisi komponen utama yang merepresentasikan halaman penuh (e.g., Halaman Daftar Mata Kuliah, Halaman Detail Tugas).
* **`src/api`**: Berisi fungsi-fungsi untuk mengelola permintaan data dan komunikasi dengan Back-End API (di Checkpoint 2 akan terhubung dengan API RISTEK).
* **`src/assets`**: Tempat penyimpanan file statis seperti gambar, ikon, atau font kustom.
* **`src/context` / `src/store`**: Digunakan untuk manajemen *state* global atau data aplikasi (jika diperlukan).
* **`public/`**: Berisi file statis yang disajikan langsung, seperti `index.html` dan logo.
* **`node_modules/`**: Berisi semua dependensi pihak ketiga yang diinstal melalui `npm install`.
