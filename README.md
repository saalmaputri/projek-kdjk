![Logo DokuWiki](Images/DokuWiki1.jpg)

## Daftar Isi
- [Sekilas Tentang](#sekilas-tentang)
- [Instalasi](#instalasi)
- [Konfigurasi](#konfigurasi)
- [Otomatisasi](#otomatisasi)
- [Cara Pemakaian](#cara-pemakaian)
- [Pembahasan](#pembahasan)
- [Referensi](#referensi)

## Sekilas Tentang
[`^ kembali ke atas ^`](#)

**DokuWiki** adalah aplikasi _wiki open source_ yang sederhana, ringan, dan tidak memerlukan database untuk berjalan. Semua data disimpan dalam bentuk file teks, sehingga instalasi dan pemeliharaannya sangat mudah. **DokuWiki** digunakan di kalangan pengguna yang membutuhkan sistem dokumentasi cepat, aman, dan efisien. **DokuWiki** dirancang untuk kolaborasi, dimana setiap orang yang memiliki akses dapat membuat, mengedit, maupun memperbarui halaman dengan mudah. Setiap perubahan yang dilakukan juga otomatis tersimpan dalam riwayat, sehingga kita bisa melihat siapa yang mengubah apa, dan mengembalikannya.  


## Instalasi
[`^ kembali ke atas ^`](#)

**Kebutuhan Sistem :**
- Unix, Linux atau Windows.
- Apache, Nginx, IIS, atau web server lain yang mendukung PHP.
- PHP 7.2+
- RAM minimal 32 Mb+


**Proses Instalasi**
1. Download DokuWiki
   - Dapat diakses melalui link dokuwiki.org
     ![Download DokuWiki](Images/DokuWiki2.png)
   - Dapat git clone melalui terminal

   ```bash
   git clone https://github.com/dokuwiki/dokuwiki
   ```
2. Pastikan XAMPP sudah terpasang pada perangkat, masukkan file DokuWiki yang sudah di download kedalam folder
   ```bash
   C:\xampp\htdocs\
   ```
3. Buka XAMPP dan start Apache
   ![XAMPP Apache](Images/DokuWiki3.png)
4. DokuWiki dapat di akses local melalui link berikut
   ```bash
   http://localhost/dokuwiki/
   ```
5. DokuWiki sudah dapat digunakan dalam localhost
   ![LocalHost DokuWiki](Images/DokuWiki4.png)


## Konfigurasi (opsional)

Setting server tambahan yang diperlukan untuk meningkatkan fungsi dan kinerja aplikasi, misalnya:
- batas upload file
- batas memori
- dll

Plugin untuk fungsi tambahan
- login dengan Google/Facebook
- editor Markdown
- dll


##  Maintenance (opsional)

Setting tambahan untuk maintenance secara periodik, misalnya:
- buat backup database tiap pekan
- hapus direktori sampah tiap hari
- dll


## Otomatisasi (opsional)

Skrip shell untuk otomatisasi instalasi, konfigurasi, dan maintenance.


## Cara Pemakaian

- Tampilan aplikasi web
- Fungsi-fungsi utama
- Isi dengan data real/dummy (jangan kosongan) dan sertakan beberapa screenshot


## Pembahasan

- Pendapat anda tentang aplikasi web ini
    - kelebihan
    - kekurangan
- Bandingkan dengan aplikasi web lain yang sejenis


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.
