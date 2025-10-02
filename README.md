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
  
    - **Kelebihan**
      1. **Mudah Diinstal dan Digunakan**: DokuWiki hanya butuh PHP dan web server (Apache/Nginx) tanpa database, jadi instalasi akan terasa cepat dan mudah. Sintaks yang digunakan sederhana, yaitu toolbar, section editing, auto-save, dan breadcrumbs, sehingga pengguna baru maupun profesional bisa langsung menulis dan mengedit halaman dengan mudah.
      2. **Kebutuhan Sistem Rendah**: DokuWiki ringan karena bisa berjalan di server dengan spesifikasi kecil, hemat RAM dan CPU, serta cocok untuk server kampus atau organisasi kecil.
      3. **Manajemen Konten Fleksibel**: Mendukung _unlimited page revisions_, kategori melalui namespace, upload dan embedding media, serta link otomatis antarhalaman, membuat pengelolaan konten menjadi rapi dan mudah dicari.
      4. **Keamanan dan Kontrol Akses**: Dilengkapi Access Control List (ACL), halaman read-only, anti-spam, dan proteksi email, Dokuwiki memberikan kontrol penuh terhadap siapa yang bisa mengakses atau mengedit konten serta melindungi dari gangguan.
      5. **Internasional dan URL Bersih**: Mendukung lebih dari 50 bahasa termasuk Bahasa Indonesia, UTF-8, serta romanization untuk URL, cocok untuk tim lokal maupun internasional dengan navigasi halaman yang rapi.
         
    - **Kekurangan**
      1. **Skalabilitas Terbatas:** Untuk organisasi besar atau wiki dengan konten sangat dinamis, DokuWiki bisa terasa kurang cepat dan fitur yang disediakan terbatas karena pendekatan yang sederhana.
      2. **Tampilan dan Pengalaman Pengguna (UI/UX):** Interface dalam Dokuwiki terlihat lebih sederhana dibanding wiki modern seperti _Confluence atau Notion_, sehingga terasa kurang menarik dan intuitif untuk pengguna yang baru menggunakan Dokuwiki.
      3. **Fitur Bawaan Terbatas:** Beberapa fungsi tambahan dalam Dokuwiki harus diinstal terlebih dahulu melalui plugin agar wiki memiliki fitur yang lengkap sesuai kebutuhan pengguna.
         
- Bandingkan dengan aplikasi web lain yang sejenis


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.
