# UAS-PakAhmadRoihan-PPL
# NAMA : MARLINDA
# KELAS : 5A TEKNIK INFORMASI

soal no 1
#no1

Hardware Schematics

Group member laptops
Software Scheme

-MySQL

-PHP

-Visual Studio Code

-Visual paradigm

Database Schema
![image](https://github.com/user-attachments/assets/87152aa8-1185-4814-b146-c65d8411032f)

Relationship Between Tables

a. Main Table: The main tables are goods, categories, and members, as this data is central to recording transactions and other information.

b. Important Relationships: Item to Category: Each item has a category (id_kategori).

Sales and Notes to Goods: Transactions related to goods sold.

Sales and Memos to Members: Transactions also record customers who make purchases.

Member Login: Each login is only valid for specific members.

Actor Scheme

Use Case diagram
![image](https://github.com/user-attachments/assets/8526a717-22b4-4a6b-ad9b-4d2775b30790)

Explanation of the diagram Login: Admins must log in before using the system.

Managing Item Data: Admins can add, edit, or delete items in the system.

Manage Stock of Goods: Admins increase or decrease the stock of available items.

Make a Purchase: Admin selects the item sold, processes checkout, and prints an invoice.

View Sales Reports: Admins can view sales reports periodically.

View Transaction History: Admins can view transactions that have occurred for record-keeping purposes.

Sequence Diagram
![image](https://github.com/user-attachments/assets/16b85c4d-6c09-42ea-a32c-5724f0c5c6e0)


Deskripsi Sequence Diagram: Aktor:

Admin Entitas website Sistem Penjualan:

Database

Modul Login

Modul Barang

Modul Penjualan

Modul Laporan

Skema Interaksi:

Admin Login:

Admin memasukkan username dan password.

Sistem memverifikasi kredensial di database.

Sistem memberikan akses jika berhasil.

Mengelola Barang:

Admin menambah/mengedit/menghapus data barang.

Sistem menyimpan perubahan di database.

Melakukan Penjualan:

Admin memilih barang untuk dijual.

Admin memasukkan jumlah barang yang dijual.

Sistem menghitung total harga dan menyimpan data transaksi.

Melihat Laporan:

Admin meminta laporan penjualan.

Sistem mengambil data dari database dan menampilkan laporan.

Activity Diagram
![image](https://github.com/user-attachments/assets/a59c068f-7646-4dcd-a9a1-7d3a74986058)


#NO2

Untuk proyek ini, bahasa pemrograman yang akan digunakan adalah PHP dengan tambahan JavaScript untuk pengembangan sisi klien, serta MySQL untuk basis data

1. Bahasa Pemrograman yang Digunakan
PHP:

PHP dipilih karena ini adalah bahasa pemrograman server-side yang sangat populer untuk pengembangan aplikasi web dinamis. Beberapa alasan memilih PHP:

Mudah dipelajari: PHP relatif mudah dipelajari bagi pemula dan memiliki dokumentasi yang luas.

Ketersediaan hosting: PHP didukung oleh hampir semua penyedia layanan hosting, sehingga lebih mudah untuk deploy aplikasi web.

Keamanan: PHP memiliki banyak fitur keamanan yang sudah ada, seperti proteksi terhadap SQL injection dan Cross-Site Scripting (XSS).

Kompatibilitas Database: PHP terintegrasi dengan MySQL secara alami dan memiliki banyak library untuk mempermudah pengelolaan database.

JavaScript:

JavaScript digunakan di sisi klien (frontend) untuk membuat antarmuka pengguna (UI) yang interaktif dan dinamis. JavaScript memungkinkan manipulasi DOM secara langsung, serta pengiriman dan pengambilan data melalui AJAX, yang meningkatkan pengalaman pengguna.

 ySQL:

MySQL dipilih sebagai sistem manajemen basis data (DBMS) karena kehandalan dan kemudahan integrasi dengan PHP. MySQL adalah salah satu database yang paling banyak digunakan dalam pengembangan aplikasi web dan memiliki fitur yang kuat serta kinerja yang tinggi untuk menangani data dalam jumlah besar.

2.Platform Pengembangan
Aplikasi berbasis Web:

Platform yang dipilih untuk pengembangan adalah aplikasi berbasis web. Hal ini memungkinkan pengguna untuk mengakses aplikasi dari perangkat apapun yang terhubung ke internet tanpa perlu menginstal perangkat lunak tambahan. Dengan menggunakan PHP di sisi server dan JavaScript di sisi klien, aplikasi dapat memberikan antarmuka yang dinamis dan dapat diakses di berbagai perangkat.

3. Perangkat Lunak Pendukung
IDE (Integrated Development Environment):

Visual Studio Code (VSCode): VSCode dipilih karena ringan, mudah digunakan, dan memiliki banyak ekstensi yang mendukung PHP, JavaScript, dan MySQL.

XAMPP atau MAMP:

XAMPP (atau MAMP untuk macOS) digunakan untuk menyediakan server lokal dengan Apache, PHP, dan MySQL, yang memungkinkan pengembangan dan pengujian aplikasi secara offline.

Git:

Digunakan untuk version control. Proyek ini akan menggunakan Git sebagai alat untuk mengelola dan melacak perubahan kode yang dilakukan oleh tim pengembangan, serta untuk kolaborasi melalui GitHub.

MySQL Workbench:

Untuk memudahkan desain dan manajemen database MySQL, MySQL Workbench digunakan. Dengan Workbench, proses pembuatan dan pengelolaan database menjadi lebih intuitif.

![GitHub - khaerun19_UAS-PakAhmadRoihan-PPL - Profile 1 - Microsoft​ Edge 03_02_2025 20_49_10](https://github.com/user-attachments/assets/8d214b73-3b7c-4f63-b023-11982a65e37b)


#no3

Gambaran proses implementasi sistem dari persiapan lingkungan kerja hingga penerapan komponen-komponen perangkat lunak. Langkah-langkah ini mencakup integrasi hardware, software, database, dan antarmuka pengguna untuk memastikan sistem berjalan sesuai desain.

Persiapan Lingkungan Kerja
Instalasi Perangkat Lunak dan Alat Pengembangan:
-Instalasi IDE: Pertama, install IDE seperti Visual Studio Code (VSCode) yang akan digunakan untuk menulis kode PHP dan JavaScript. Pastikan VSCode terkonfigurasi dengan ekstensi untuk PHP, JavaScript, dan MySQL.

-Instalasi XAMPP/MAMP: Install XAMPP (atau MAMP untuk macOS) untuk menyediakan server lokal yang mencakup Apache, PHP, dan MySQL. Ini akan menjadi platform pengujian untuk aplikasi berbasis web yang sedang dikembangkan.

-Instalasi Git: Instal Git untuk kontrol versi, sehingga dapat melacak perubahan kode dan kolaborasi dengan tim pengembang.

-MySQL Workbench: Instal MySQL Workbench untuk desain dan manajemen basis data.

-Konfigurasi Database:

Buat database baru di MySQL dengan nama tb_anugrah (sesuai dengan struktur yang sudah direncanakan). Buat tabel yang diperlukan dalam database sesuai dengan desain yang telah dibuat, seperti detail, pesanan, masuk, pesanan_produk, dan user. Siapkan hubungan antar tabel (relasi) menggunakan foreign keys jika diperlukan untuk memastikan integritas data.

-Pengaturan Server Lokal:

Pastikan XAMPP/MAMP berjalan dengan baik dan Apache serta MySQL dapat diakses melalui localhost. Uji apakah PHP dapat dijalankan dengan membuat file PHP sederhana dan mengaksesnya melalui browser.

Pengembangan Aplikasi
-Desain dan Pengembangan Antarmuka Pengguna (Frontend):

HTML, CSS, dan JavaScript digunakan untuk membuat tampilan antarmuka pengguna. Halaman seperti login.php, dashboard.php, produk.php, dan pesanan.php dikembangkan dengan elemen-elemen HTML dan CSS yang bersih dan responsif. Gunakan JavaScript untuk menambah interaktivitas, seperti pengambilan data secara dinamis melalui AJAX, validasi formulir di sisi klien, dan manipulasi DOM untuk memberikan pengalaman pengguna yang lebih baik.

-Pengembangan Backend:

PHP digunakan untuk menangani logika aplikasi di sisi server. Ini termasuk: Koneksi ke database menggunakan db.php. Menangani proses autentikasi dan manajemen sesi pada login.php. Memproses data yang dikirimkan dari formulir dan melakukan operasi CRUD pada pesanan.php, produk.php, dan detail_pesanan.php. Mengubah status pesanan melalui ubah_status.php dan mengelola laporan pada laporan.php. Kode PHP akan mengakses dan memodifikasi data di database tb_anugrah sesuai dengan permintaan pengguna.

-Integrasi Sistem Keamanan:

Terapkan prosedur keamanan standar seperti hashing password menggunakan fungsi PHP password_hash() untuk melindungi data pengguna. Gunakan prepared statements di PHP untuk mencegah SQL Injection saat berinteraksi dengan database. Terapkan pengamanan untuk melindungi aplikasi dari Cross-Site Scripting (XSS) dan Cross-Site Request Forgery (CSRF).

Pengujian Sistem
-Pengujian Fungsional:

Uji setiap fitur aplikasi untuk memastikan bahwa semua fungsionalitas berfungsi seperti yang diinginkan, mulai dari login, manajemen produk, hingga pengelolaan pesanan. Lakukan pengujian terhadap form input untuk memastikan data yang dimasukkan ke dalam database akurat dan tidak ada kesalahan logika dalam aplikasi.

-Pengujian Keamanan:

Lakukan uji keamanan seperti penetration testing untuk mencari potensi celah di aplikasi. Pastikan bahwa session hijacking dan SQL injection tidak bisa dilakukan oleh pihak yang tidak berwenang.

-Pengujian Performa:

Uji performa aplikasi di server lokal dengan beberapa beban pengguna untuk memastikan aplikasi dapat menangani permintaan dengan cepat dan tanpa masalah.

Integrasi dan Penyebaran
-Integrasi Sistem:

Setelah semua komponen diuji secara terpisah, integrasikan frontend dan backend secara penuh. Pastikan komunikasi antara frontend (JavaScript) dan backend (PHP) berjalan lancar. Penggunaan AJAX untuk pengiriman data secara dinamis dan pemrosesan di PHP harus berfungsi tanpa hambatan.

-Penyebaran ke Server Produksi:

Setelah aplikasi siap untuk digunakan, deploy aplikasi ke server produksi. Pastikan konfigurasi server di hosting sudah sesuai, seperti pengaturan domain, basis data, dan keamanan server. Terapkan SSL untuk enkripsi data yang dikirimkan antara klien dan server.

Pemeliharaan dan Pembaruan
-Pemantauan dan Logging:

Pasang alat pemantauan untuk memantau performa server dan aplikasi. Gunakan log error untuk melacak masalah yang muncul selama penggunaan.

-Pembaruan Sistem:

Secara rutin lakukan pembaruan terhadap aplikasi, memperbaiki bug yang ditemukan, serta meningkatkan fitur dan keamanan sistem.

#4

Metode Pengujian: Black-Box Testing
Black-box testing berfokus pada pengujian fungsionalitas aplikasi tanpa melihat implementasi internal dari kode sumber. Pengujian ini berfokus pada input dan output aplikasi untuk memastikan aplikasi bekerja sesuai dengan persyaratan pengguna dan spesifikasi sistem. Pengujian ini akan mencakup jenis-jenis pengujian berikut:

Jenis Pengujian Black-Box:

Unit Testing:

Unit testing akan menguji bagian-bagian terkecil dari aplikasi seperti fungsi atau metode individual untuk memastikan bahwa setiap unit kode berfungsi dengan benar. Misalnya, pengujian validasi form login untuk memastikan hanya pengguna yang valid yang dapat masuk.

Hasil Pengujian:

Jika fungsi login menerima input yang benar (username dan password yang valid), maka pengguna dapat diarahkan ke dashboard. Sebaliknya, input yang salah akan menghasilkan pesan error.

#5

Identifikasi Masalah Kesalahan pencatatan transaksi secara manual, seperti total pembayaran atau stok barang.
Kesulitan dalam mengetahui stok barang secara real-time.

Proses pembuatan laporan yang memakan waktu karena dilakukan secara manual.

Risiko kehilangan data akibat tidak adanya sistem terpusat.

Kurangnya efisiensi dalam pengelolaan data barang dan transaksi.

Rumusan Masalah Bagaimana merancang sistem penjualan berbasis website untuk mempermudah pencatatan transaksi di toko bangunan?
Bagaimana sistem ini dapat membantu memantau stok barang secara real-time?

Bagaimana cara mengintegrasikan pembuatan laporan otomatis ke dalam sistem?

Bagaimana memastikan keamanan dan akurasi data dalam sistem penjualan berbasis website?

Solusi
Sistem Penjualan Berbasis Website
Develop a web-based sales system that allows automatic recording of transactions and stored in a database. Every transaction made will be directly integrated into the system without the need for manual recording.

Real-Time Stock Monitoring
Provides a stock management feature that automatically updates the number of items after a transaction. It uses a MySQL database to store stock data and AJAX to display stock data in real-time in the admin dashboard.

Automated Report Generation
Developed an automated reporting module that generates sales and stock reports based on transaction data. Reports can be exported in PDF/Excel format and displayed in graph form for easier analysis.

Data Security and Accuracy
