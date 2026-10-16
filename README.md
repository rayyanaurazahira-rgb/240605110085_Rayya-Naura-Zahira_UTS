# Aplikasi Katalog Wisata Indonesia

Aplikasi mobile berbasis Flutter yang dikembangkan untuk memenuhi tugas Ujian Tengah Semester (UTS) mata kuliah Mobile Programming. Aplikasi ini menyajikan informasi katalog destinasi wisata di Indonesia dengan antarmuka yang modern, responsif, dan interaktif.

## Fitur & Struktur Halaman
1. **MainScreen (`main_screen.dart`)**: Menampung navigasi `BottomNavigationBar` untuk berpindah antarhalaman utama.
2. **Beranda (`home_page.dart`)**: Menampilkan ucapan selamat datang, pencarian dummy, daftar kategori wisata, serta rekomendasi populer berformat *horizontal scroll*.
3. **Daftar Destinasi (`list_page.dart`)**: Menampilkan 10 data destinasi wisata secara vertikal (`ListView.builder`) lengkap dengan gambar, harga, lokasi, dan rating.
4. **Detail Destinasi (`detail_page.dart`)**: Menampilkan informasi rinci dan deskripsi destinasi yang dipilih melalui navigasi `Navigator.push`.

## Struktur Data
Data aplikasi dikelola secara terstruktur melalui model `Destination` (`models/destination.dart`) dan disimpan dalam bentuk list dummy (`data/dummy_data.dart`). Struktur data ini dirancang agar siap diintegrasikan dengan REST API di masa mendatang.

## Cara Menjalankan Aplikasi
1. Pastikan Flutter SDK sudah terpasang di perangkat Anda.
2. Clone repositori ini:
   ```bash
   git clone <https://github.com/rayyanaurazahira-rgb/240605110085_Rayya-Naura-Zahira_UTS>