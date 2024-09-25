# FaceTracker
# FaceTracker Project Overview

## Pendahuluan

FaceTracker adalah perpustakaan untuk pelacakan wajah deformable yang ditulis dalam C++ menggunakan OpenCV. Awalnya dikembangkan oleh Jason Saragih dan dikelola oleh Kyle McDonald, proyek ini dirancang untuk memberikan solusi efektif dalam pelacakan wajah menggunakan metode yang inovatif. Meskipun repositori ini tidak lagi dipelihara karena tantangan dalam memperbarui ke OpenCV 4, FaceTracker tetap relevan sebagai referensi dalam penelitian dan aplikasi pelacakan wajah.

## Isi

### Deskripsi Proyek

FaceTracker menggunakan pendekatan subspace constrained mean-shifts untuk melakukan pelacakan wajah yang akurat. Dengan menggunakan model pra-latih, pengguna dapat dengan mudah mengintegrasikan FaceTracker ke dalam aplikasi mereka. Proyek ini telah dilisensikan di bawah MIT sejak 8 April 2020, memungkinkan penggunaan komersial tanpa batasan.

### Fitur Utama

- **Pelacakan Wajah Deformable**: Memungkinkan deteksi dan pelacakan wajah dalam berbagai pose.
- **Kompatibilitas**: Tersedia untuk berbagai platform, termasuk Android dan openFrameworks.
- **Performa**: Meski mungkin lambat pada langkah deteksi, ada opsi untuk memindahkan proses pelacakan ke thread terpisah untuk meningkatkan performa.

### Instalasi

Untuk menginstal FaceTracker, pengguna perlu menginstal OpenCV (versi 2 atau 3), mengkloning repositori, dan membangun pustaka dengan menjalankan perintah `make`. Panduan instalasi disediakan untuk OS X dan Ubuntu, serta pengaturan direktori model yang diperlukan agar aplikasi dapat berjalan dengan baik.

### Penggunaan

Pengguna dapat menjalankan FaceTracker dengan berbagai opsi untuk mengonfigurasi model pelacakan, konektivitas, dan pengaturan scaling gambar. Contoh penggunaan yang disediakan juga membantu pengguna dalam menyesuaikan pengaturan untuk mencapai kinerja optimal.

## Kesimpulan

FaceTracker adalah alat yang kuat untuk pelacakan wajah yang dapat digunakan dalam berbagai aplikasi, mulai dari penelitian hingga pengembangan produk komersial. Meskipun tidak lagi dipelihara, dokumentasi dan fitur-fitur yang ada menjadikannya sebagai sumber daya berharga bagi pengembang yang tertarik dalam pelacakan wajah. Dengan lisensi MIT, FaceTracker memberikan fleksibilitas bagi pengguna untuk mengintegrasikannya ke dalam proyek mereka.

## Source
https://github.com/kylemcdonald/FaceTracker
