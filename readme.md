<p align="center"><img src="public/img/logo_new_white.png"></p>
<p align="center">Socibersh - Laravel</p>

## Deskripsi Proyek

"Socibersh Marketplace Kosmetik adalah destinasi online yang menyajikan berbagai produk kecantikan terbaik dari berbagai merek terkemuka. Dari skincare hingga makeup, Socibersh menyediakan beragam produk kosmetik berkualitas untuk memenuhi kebutuhan perawatan kecantikan Anda. Dengan koleksi yang luas dan beragam, serta fitur-fitur seperti rekomendasi produk, dan kemudahan pembayaran, Socibersh memastikan pengalaman berbelanja kosmetik yang menyenangkan dan memuaskan. Temukan produk-produk terbaru dan favorit Anda, serta temukan kecantikan yang sesuai dengan gaya dan preferensi Anda di Socibersh Marketplace Kosmetik."

## Kelompok Kerja
- Ikhsan Fauzan
- Nur Hidayat
- Riyan

## Fitur Utama
Fitur utama dari aplikasi ini mencakup:

1. **Pengelolaan Produk**: Admin dapat menambahkan, mengedit, dan menghapus produk-produk kosmetik dari aplikasi. Ini termasuk pengelolaan kategori, gambar, deskripsi, dan harga produk.

2. **Checkout yang Mudah**: Pengguna dapat dengan mudah menambahkan produk ke keranjang belanja dan melakukan proses checkout dengan beberapa langkah sederhana. Pada proses checkout, pengguna memiliki pilihan metode pembayaran yang beragam, seperti pembayaran melalui PayPal, transfer bank, atau pembayaran saat pengiriman.

3. **Pencarian Produk**: Pengguna dapat dengan mudah mencari produk yang diinginkan menggunakan fitur pencarian yang tersedia di aplikasi. Ini membantu pengguna menemukan produk yang mereka butuhkan dengan cepat.

4. **Kontak dan Dukungan**: Aplikasi menyediakan halaman kontak di mana pengguna dapat mengirimkan pesan atau pertanyaan kepada admin. Ini memungkinkan pengguna untuk mendapatkan dukungan jika mereka mengalami masalah atau memiliki pertanyaan tentang produk atau layanan.

5. **Bahasa Multi**: Aplikasi mendukung beberapa bahasa, memungkinkan pengguna untuk memilih bahasa yang mereka inginkan saat menggunakan aplikasi.

6. **Dashboard Admin**: Admin memiliki akses ke dashboard admin yang memungkinkan mereka melihat laporan penjualan, mengelola pesanan, mengelola pengguna, dan mengelola konten aplikasi lainnya.

7. **Slider Promosi**: Admin dapat mengatur slider promosi di halaman beranda untuk menampilkan produk-produk unggulan atau penawaran khusus kepada pengguna.

8. **Pesanan Cepat**: Pengguna dapat menggunakan fitur pesanan cepat untuk langsung melakukan pesanan tanpa perlu membuat akun atau melakukan proses checkout yang panjang.

9. **Responsif dan Ramah Pengguna**: Aplikasi dirancang responsif dan ramah pengguna, memastikan pengalaman pengguna yang baik baik pada perangkat desktop maupun mobile.

Fitur-fitur ini dirancang untuk memberikan pengalaman belanja kosmetik yang menyenangkan dan mudah bagi pengguna sambil memberikan alat yang kuat bagi admin untuk mengelola toko mereka.\


## Installation
1. Run `composer install` to install dependencies.
2. Copy `env.example` to `.env` and update the following:
   - Set your database credentials.
   - Set your `APP_URL`.
3. Run `php artisan migrate` to migrate the database.
4. Run `php artisan db:seed` to seed the database.
5. Run `php artisan storage:link` to create a symbolic link from "public/storage" to "storage/app/public".

## Login to administration
Access the administration panel at: `http://yourdomain.com/admin`
- Email: admin@example.com
- Password: admin
