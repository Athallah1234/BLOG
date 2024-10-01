# BLOG

Blog Web adalah platform online yang memungkinkan pengguna untuk mempublikasikan artikel, pemikiran, atau konten lainnya secara berkala. Biasanya, blog terdiri dari postingan yang diurutkan berdasarkan tanggal dengan konten terbaru di bagian atas. Pengguna bisa membuat dan mengelola konten melalui antarmuka yang mudah digunakan, sering kali didukung oleh fitur-fitur seperti sistem komentar, kategori, tag, dan manajemen pengguna. Teknologi yang umum digunakan untuk membangun blog mencakup HTML, CSS, PHP, dan database seperti MySQL untuk menyimpan data artikel dan pengguna.

## Fitur Utama

- **Pembuatan & Pengelolaan Postingan:** Buat, edit, dan hapus artikel dengan antarmuka pengguna yang mudah digunakan.
- **Sidebar Postingan Terbaru:** Pembaca dapat dengan mudah menemukan artikel terbaru Anda melalui sidebar yang selalu diperbarui.
- **Postingan Terkait:** Menyediakan rekomendasi artikel yang relevan bagi pembaca di setiap halaman artikel.
- **Sistem Pencarian Langsung:** Temukan artikel dengan cepat menggunakan fitur pencarian langsung yang interaktif.
- **Pagination Dinamis:** Lihat postingan dengan nyaman melalui pagination yang dioptimalkan.
- **Validasi Formulir:** Setiap entri di blog diperiksa secara otomatis untuk menjaga kualitas data.
- **Komentar di Postingan** - Tambahkan sistem komentar untuk berinteraksi dengan pembaca.
- **Kategori & Tag** - Memungkinkan pengguna untuk mengkategorikan artikel mereka agar lebih mudah dicari.
- **Otentikasi Pengguna** - Menambahkan fitur registrasi dan login untuk penulis artikel.

## Teknologi yang Digunakan

- **PHP** untuk backend.
- **MySQL** untuk manajemen database.
- **CSS** untuk desain yang responsif dan modern.

## Cara Installasi

- Download File [Disini](https://github.com/Athallah1234/BLOG/releases)
- Masukkan ke dalam directory ``htdocs`` (xampp) / ``www`` (laragon)
- extract file Blog.rar pada direktori ``htdocs``(xampp) / ``www`` (laragon)
- Konfigurasi file db.php pada direktory ``/Blog/config/db.php`` (jika dibutuhkan)
- jalankan server xampp/laragon
- lalu masukkan file sql ke database MySQL/MariaDB atau Database Client seperti phpmyadmin di
  ``localhost:8080/phpmyadmin`` (untuk laragon)
  ``localhost/phpmyadmin`` (untuk xampp)
- selamat website berhasil dijalankan

jika terdapat kendala bisa konsul [Disini](https://github.com/Athallah1234/BLOG/issues/1)

## Pertanyaan yang Sering Diajukan (FAQ)

### 1. **Apakah blog ini bisa digunakan secara gratis?**
Ya, blog ini sepenuhnya open-source dan bisa digunakan secara gratis dengan lisensi MIT. Anda bebas menggunakannya dan memodifikasinya sesuai kebutuhan.
### 2. **Bagaimana cara menambahkan artikel baru ke blog ini?**
Anda bisa menambahkan artikel baru dengan login sebagai admin, lalu klik tombol Manage Posts kemudian menggunakan fitur Create New Post di dashboard admin.
### 3. **Apakah blog ini responsif di semua perangkat?**
Tidak, desain blog ini belum dioptimalkan untuk tampil baik di perangkat desktop, tablet, dan mobile. (masih dalam bentuk tampilan desktop)
### 4. **Apakah ada rencana untuk menambahkan fitur keamanan tambahan, seperti CAPTCHA?**
Kami telah menambahkan fitur CAPTCHA dan validasi keamanan tambahan pada Login dan Register Page.

## Panduan Penggunaan

Setelah berhasil menginstal blog website ini, Anda dapat mulai menggunakan fitur-fitur yang ada. Berikut adalah panduan singkat untuk memulai:

A. Management Category

### 1. Membuat Kategori Baru
Untuk membuat kategori baru, ikuti langkah-langkah berikut:
- Login ke dashboard admin.
- Klik Tombol Manage Category
- Pilih menu "Create A Category" di sidebar.
- Isi judul kategori Anda.
- Klik tombol **Create Category** untuk menerbitkan artikel.

### 2. Mengedit Postingan
Untuk mengedit kategori yang sudah ada:
- Buka dashboard admin dan navigasikan ke menu "Manage Category".
- Klik tombol **Edit** di sebelah kategori yang ingin Anda ubah.
- Lakukan perubahan dan klik **Update Category** untuk menyimpan perubahan.

### 3. Menghapus Postingan
Untuk menghapus kategori yang sudah ada:
- Navigasikan ke menu "Manage Category" di dashboard admin.
- Klik tombol **Delete** di sebelah artikel yang ingin dihapus.
- Konfirmasikan penghapusan dan artikel akan dihapus dari sistem.

B. Management Tag

### 1. Membuat Tag Baru
Untuk membuat tag baru, ikuti langkah-langkah berikut:
- Login ke dashboard admin.
- Klik Tombol Manage Tags.
- Pilih menu "Create A Tag" di sidebar.
- Isi judul tag Anda.
- Klik tombol **Create Tag** untuk menerbitkan artikel.

### 2. Mengedit Tag
Untuk mengedit tag yang sudah ada:
- Buka dashboard admin dan navigasikan ke menu "Manage Tag".
- Klik tombol **Edit** di sebelah kategori yang ingin Anda ubah.
- Lakukan perubahan dan klik **Update Tag** untuk menyimpan perubahan.

### 3. Menghapus Tag
Untuk menghapus kategori yang sudah ada:
- Navigasikan ke menu "Manage Tag" di dashboard admin.
- Klik tombol **Delete** di sebelah artikel yang ingin dihapus.
- Konfirmasikan penghapusan dan artikel akan dihapus dari sistem.

C. Management Post

### 1. Membuat Postingan Baru
Untuk membuat postingan baru, ikuti langkah-langkah berikut:
- Login ke dashboard admin.
- klik tombol Manage Posts
- Pilih menu "Create New Post" di sidebar.
- Isi judul, konten, dan kategori artikel Anda.
- Klik tombol **Publish** untuk menerbitkan artikel.

### 2. Mengedit Postingan
Untuk mengedit postingan yang sudah ada:
- Buka dashboard admin dan navigasikan ke menu "Manage Posts".
- Klik tombol **Edit** di sebelah artikel yang ingin Anda ubah.
- Lakukan perubahan dan klik **Update Post** untuk menyimpan perubahan.

### 3. Menghapus Postingan
Untuk menghapus postingan yang sudah ada:
- Navigasikan ke menu "Manage Posts" di dashboard admin.
- Klik tombol **Delete** di sebelah artikel yang ingin dihapus.
- Konfirmasikan penghapusan dan artikel akan dihapus dari sistem.

## Keamanan

Kami memperhatikan aspek keamanan dalam pengembangan proyek ini. Berikut adalah beberapa langkah keamanan yang telah diterapkan:

- **Validasi Input:** Setiap input dari pengguna divalidasi untuk mencegah serangan seperti SQL Injection dan XSS.
- **Prepared Statements:** Penggunaan prepared statements untuk semua query ke database, memastikan keamanan dari serangan SQL Injection.
- **Proteksi User Enumeration:** Informasi tentang apakah username atau email tertentu terdaftar tidak akan ditampilkan kepada pengguna untuk mencegah percobaan brute force.
- **Hashing Password:** Semua password pengguna di-hash menggunakan algoritma yang aman seperti `bcrypt` sebelum disimpan di database.
- **Rate Limiting:** Rencana penerapan rate limiting pada fitur login dan registrasi untuk menghindari serangan brute force.
- **CAPTCHA:** Sistem CAPTCHA akan segera ditambahkan pada halaman login dan registrasi untuk menambah lapisan keamanan.

Jika Anda menemukan masalah keamanan atau celah keamanan, segera hubungi kami di security@yourwebsite.com.

## Lisensi
Proyek ini dilisensikan di bawah Apache-2.0 license. Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.
