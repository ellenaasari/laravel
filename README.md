# LARAVEL CRUD
Laravel CRUD merupakan operasi manipulasi dan pengolahan data di database menggunakan framework Laravel. 
## Fitur
1. Form Nama, Kelas, Jurusan, Alamat (Untuk menampilkan data yang di masukkan).
2. Button-Tambah (Untuk menambah data yang sudah di masukkan).
3. Table (Untuk menampilkan data yang sudah di masukkan/tambahkan).
4. Button-Edit (Untuk mengedit data yang sudah di masukkan/tambah pada table).
5. Button-Hapus (Untuk menghapus data yang ada pada table).
## User
### Local Instalation
1. Download **XAMPP**
2. Jalankan XAMPP Control Panel dan **Klik** Start (Mulai) pada Apache dan Mysql
3. Copy File laravelcrud-master.zip ke Folder **C://xampp/htdocs/** Kemudian Extract to file
### Creating Database
1. Masuk ke laman Browser kemudian tulis pada Address Bar http://localhost/phpmyadmin
2. Buat database dengan nama siswa_app
3. Import database **siswa_app.sql**
## Siswa Konfiguration
### Konfigurasi Database
1. Edit File database.php yang ada pada Folder application/config/
2. Kemudian Pastikan **Hostname** Bernilai **localhost**
3. **Username** bernilai **root**
4. **Password** dibiarkan **kosong**
5. Database bernilai siswa_app **Note: Sesuaikan dengan nama database yang dibuat**
6. Simpan File
### Konfigurasi Base URL
1. Edit File config.php yang ada pada Folder application/config/
2. Kemudian pastikan variable $config['base_url'] bernilai 'http://localhost/siswa/
3. Simpan File
