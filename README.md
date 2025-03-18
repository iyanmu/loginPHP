# LoginPHP

Sebuah sistem login sederhana yang dibangun menggunakan PHP dan MySQL. Proyek ini dirancang untuk memungkinkan pengguna mendaftar, login, dan mengakses halaman yang dilindungi.

## Demo

Anda dapat mencoba demo proyek ini di [Demo LoginPHP](https://iyanmu.github.io/loginPHP/).

> **Catatan**: Karena ini adalah proyek PHP yang membutuhkan server backend, demo di GitHub Pages mungkin tidak berfungsi sepenuhnya. Untuk mencoba fitur lengkap, jalankan proyek ini di lingkungan server lokal seperti XAMPP, Laragon, atau server PHP lainnya.

## Preview

![Screenshot 2025-03-18 091056](https://github.com/user-attachments/assets/02f064e3-3bf5-4f6e-80fe-772ed7e24d24)

## Fitur

- **Registrasi Pengguna**: Pengguna dapat mendaftar dengan mengisi formulir registrasi.
- **Login Pengguna**: Pengguna yang terdaftar dapat login menggunakan email dan password.
- **Halaman Terproteksi**: Halaman yang hanya dapat diakses setelah login.
- **Validasi Formulir**: Validasi input pada sisi server dan client.
- **Keamanan**: Password di-hash menggunakan `password_hash()` untuk keamanan.

## Teknologi yang Digunakan

- **PHP**: Bahasa pemrograman server-side untuk menangani logika backend.
- **MySQL**: Database untuk menyimpan data pengguna.
- **HTML/CSS**: Struktur dan tampilan antarmuka pengguna.
- **JavaScript**: Untuk validasi sisi client dan interaktivitas.

## Cara Menjalankan Secara Lokal

### Persyaratan
- PHP (versi 7.0 atau lebih baru)
- MySQL/MariaDB
- Web server (seperti Apache, Nginx, atau XAMPP)

### Langkah-langkah

1. **Clone repositori ini**:
   ```bash
   git clone https://github.com/iyanmu/loginPHP.git
