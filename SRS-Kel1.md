<html>
<body>
<div align="right"><h1> Software Requirements Spesification</h1></div>

<p align="right"><b>Version 1.7 </b><br>
<p align="right">28 Maret 2018</b>
<p align="right">
</p>

<p align="center"><b>Manajemen Administrasi Data Kependudukan Desa Lohbener <br>
</b>
<p align="center">Kelompok 1 <br>
 Hilmy Lazuardi            (1603099)<br>
 Ismatul Maula    (1603100)<br>
 jakaria       (1603101)<br><br><br>

<p align="center"><b>Jurusan Teknik Informatika</b><br>
<p align="center"><b>Politeknik Negeri Indramayu</b>
<p align="center"><b>2018</b>
</p>
</body>
</html>

**BAB I Pendahuluan**
----------
1.1 Tujuan
----------
Dokumen Software Requirement Specification (SRS) merupakan dokumen spesifikasi perangkat lunak untuk membangun "Sistem Informasi Alumni SMAIT Al-Ittihad Rumbai". Dokumen ini dibangun untuk memudahkan para guru SMAIT Al-Ittihad untuk melihat dan menyimpan data para alumni SMAIT Al-Ittihad sehingga dokumen ini dapat dijadikan acuan teknis untuk membangun perangkat lunak "Sistem Informasi Alumni SMAIT Al-Ittihad Rumbai".

1.2 Lingkup
----------
Sistem Informasi Alumni SMAIT Al-Ittihad Rumbai merupakan sistem yang kami bangun untuk mempermudah guru SMAIT Al-Ittihad Rumbai dalam melihat informasi para alumni dan memudahkan dalam menampilkan data-datanya.

1.3 Akronim, Singkatan, Definisi
----------
| Istilah | Definisi |
| ------ | ------ |
| SRS |Software Requirement Specification|
| Login | Digunakan untuk mengakses web |
| Software Requirement Specification | Perangkat lunak yang akan dibuat untuk menjembatani komunikasi pembuat dengan pengguna |
| Use Case | Situasi dimana sistem digunakan untuk memenuhi satu atau lebih kebutuhan pemakaian |

1.4   Referensi
----------
Referensi yang digunakan dalam pengembangan perangkat lunak ini adalah :
- http://hasantarmizi.blogspot.co.id/2017/04/pengertian-sublime-text.html
- IEEE. IEEE Std 830-1998 IEEE Recommended Practice for Software  Requirements Specifications. IEEE Computer Society, 1998.
- _SRSExample-webapp.pdf_

1.5   Overview
----------

Bab selanjutnya yaitu menjelaskan sistem yang diterapkan pada web. Menjelaskan gambaran umum dari web, sistem interface web dan alur sistemnya. Bab terakhir menjelaskan tentang setiap fungsi yang digunakan secara teknisnya. Pada bab 2 dan 3 merupakan deskripsi dari aplikasi yang akan diterapkan pada web yang dibuat.

**BAB II Gambaran umum**
----------
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari. Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah di daerah pekanbaru riau tepatnya di  kecamatan Rumbai. Kasus yang kami peroleh pembuatan Sistem Informasi Pencatatan Data Alumni. Maka dari itu kami sebagai software developer merancang sebuah sistem sesuai dengan kebutuhan SMA Al-Ittihad dengan menerapkan Sistem Informasi yang dapat melakukan pencatatan terhadap data alumni. Sehingga memudahkan guru bk dalam menginputkan data-data alumni dan siswa dapat melihat data yang sudah diinputkan. Software yang kami buat ini berbasis website dimana website sebagai admin. Sistem yang kami buat di dalamnya terdapat data alumni dan data pengguna( untuk guru bk ), data alumni ( untuk siswa ). Berikut akan kami jelaskan sistem software kami, admin fungsi utama yaitu :
   - Input Nama Siswa
   - Input Perguruan Tinggi
   - Input Jurusan
   - Input Provinsi/Kota
   - Input Jalur
   - Input Tahun
     
   Berikut ini fungsi user dalam bentuk grafik :
   - View Nama Siswa
   - View Perguruan Tinggi
   - View Jurusan
   - View Provinsi/Kota
   - View Jalur
   - View Tahun

2.1   Perspektif produk
----------
Sistem Informasi Alumni SMAIT Al-Ittihad adalah sebuah sistem administrasi data yang diaplikasikan pada website. Terdapat 2 jenis yaitu guru BK, dan siswa. Pengolahan data di kelola oleh guru BK dan siswa hanya dapat melihat dan mencari informasi pada website.

Pada sistem informasi alumni ini akan menampilkan data alumni yang sudah diinputkan oleh guru bk.

**2.1.1 Antarmuka Sistem**

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase1.jpeg)

Sistem informasi alumni ini memiliki 2 user yaitu guru bk dan admin. Siswa mempunyai fungsi yaitu melakukan view dan mencari data alumni. Guru bk bertugas untuk mengelola data, supaya data bisa di akses oleh siswa.

**2.1.2 Antarmuka Pengguna**

**Mockup Guru BK ( Website )**

|  |  |
|--|--|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanMasuk.jpeg) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanAngkatan.jpeg) Pada halaman ini nantinya akan ditampilkan data angkatan.|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanDataAlumni.jpeg) Pada halaman ini akan ditampilkan data-data alumni | ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanTambahAlumni.jpeg) Halaman ini akan ditampilkan ketika admin ingin melakukan penambahan terhadap data alumni|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanEditAlumni.jpeg) Halaman ini akan ditampilkan ketika admin ingin melakukan pengeditan terhadap data alumni| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanDataPengguna.jpeg) Pada Halaman ini akan ditampilkan data-data user|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanTambahPengguna.jpeg) Halaman ini akan ditampilkan ketika admin ingin melakukan penambahan terhadap data pengguna| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Prototype-GuruBK/HalamanEditPengguna.jpeg) Halaman ini akan ditampilkan ketika admin ingin melakukan pengeditan terhadap data pengguna| |
 
**2.1.3 Antarmuka Perangkat Keras**

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/Diagram.jpeg)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Alumni SMAIT Al-Ittihad antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Alumni SMAIT Al-Ittihad antara lain :
1. Kabel Lan UTP RJ45
2. Modem
3. Wifi

**2.1.6 Batasan Memori**

Tidak ada

**2.1.7 Operasi-Operasi**

| Operasi | Fungsi |
| ------ | ------ |
| Login | Digunakan untuk mengakses web |
| Input Data | Digunakan untuk memasukkan data-data |
| Kembali | Digunakan untuk kembali ke halaman sebelumnya |
| Hapus | Digunakan untuk menghapus data |
| Edit | Digunakan untuk mengubah data |
| View | Digunakan untuk menampilkan data |
| Simpan | Digunakan untuk menyimpan data |

**2.1.8 Kebutuhan Adaptasi**

Tidak ada
   
2.2 Spesifikasi Kebutuhan Fungsional
----------
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase2.jpeg)
   
**2.2.1 Guru BK Masuk Ke Sistem**

Use Case: Guru bk masuk ke sistem

Diagram : 
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase3.jpeg)

Deskripsi singkat :
Guru membuat akun terlebih dahulu agar dapat masuk ke sistem.

Deskripsi langkah-langkah :
1. Guru masuk ke sistem dengan username dan password
2. Sistem melakukan validasi masuk sistem
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Guru BK masuk ke sistem
   
**2.2.2 Siswa Masuk Ke Sistem**

Use Case: Siswa masuk ke sistem

Diagram: 
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase4.jpeg)

Deskripsi singkat :
Siswa masuk ke sistem dengan mengisi form masuk.

Deskripsi langkah-langkah :
1. Siswa masuk ke sistem dengan username dan password
2. Sistem melakukan validasi masuk sistem
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.2, Siswa masuk ke sistem

**2.2.3 Guru BK Mengelola Data Alumni**

Use Case: Guru bk mengelola data alumni

Diagram :
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase5.jpeg)

Deskripsi singkat :
Guru bk dapat mengelola data alumni.

Deskripsi langkah-langkah :
1. Sistem menampilkan data Alumni
Guru BK dapat memilih tombol tambah data, edit, dan hapus untuk melakukan pengelolaan data
Sistem akan menampilkan data alumni terbaru jika guru bk melakukan pengelolaan data.

Xref: Bagian 3.2.3, Guru bk mengelola data alumni
      
**2.2.4 Guru BK Mengelola Data Pengguna**

Use Case: Guru bk mengelola data pengguna

Diagram:
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase6.jpeg)
      
Deskripsi singkat :
Sistem akan menampilkan form pengguna dan guru bk dapat menambah dan mengedit pengguna sesuai kebutuhan.

Deskripsi langkah-langkah :
1. Guru bk mengklik menu data pengguna, lalu guru bk dapat memilih tombol tambah, edit, dan hapus untuk melakukan pengelolaan terhadap data pengguna.
2. Sistem akan menyimpan data user ke database dan menampilkan data pengguna yang dipilih.
Guru bk bisa menghapus hak akses pengguna.

Xref: Bagian 3.2.4, Mengelola data user

**2.2.5 Siswa Melihat Data Alumni**

Use Case: Melihat data alumni

Diagram:
![](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/UseCase7.jpeg)

Deskripsi singkat :
Sistem akan menampilkan data alumni dan siswa dapat melihat data alumni.

Deskripsi langkah-langkah :
1. Siswa berhasil melakukan login
2. Sistem menampilkan halaman beranda yang berisi data alumni.

Xref: Bagian 3.2.5, Melihat data alumni
   
2.3   Spesifikasi Kebutuhan Non-Fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat Lunak dapat dipakai di semua platofrm  OS ( guru bk dan siswa ) 
 
2.4   Karakteristik Pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-Batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-Asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan"Anda telah melebihi batas maksimum".

2.7   Kebutuhan Penyeimbang
----------
Tidak ada

BAB III Requirement specification
----------
3.1 Persyaratan Antarmuka Eksternal
----------
Salah satu cara mengakses website ini yaitu dengan hak akses yang diberikan oleh guru BK, login melalui website ini dengan mencantumkan username kemudian sistem akan mencocokkan username dan password. Setelah login berhasil guru BK dapat melihat data-data dari alumni SMAIT Al-Ittihad.
      
3.2 Functional Requirement
----------
Logika struktur terdapat pada bagian 3.3.1
      
**3.2.1 Kepala desa Login**

|  |  |
|--|--|
| Nama Fungsi | Guru bk masuk ke sistem |
| Xref | Bagian 2.2.1, Guru bk masuk ke sistem |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman masuk |
| Basic Path | 1. Guru bk mengisi form masuk dengan username dan password <br> 2. Guru bk mengklik tombol login <br> 3. Sistem melakukan validasi masuk <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Guru BK dapat masuk ke sistem dan mengakses Sistem Alumni SMAIT Al-Ittihad |
| Exception Push | Username dan password salah |
      
**3.2.2 Siswa Masuk Ke Sistem**

|  |  |
|--|--|
| Nama Fungsi | Siswa masuk ke sistem |
| Xref | Bagian 2.2.2, Siswa masuk ke sistem |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman masuk |
| Basic Path | 1. Siswa mengisi form login dengan username/email dan password <br> 2. Siswa mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5.Bila gagal sistem akan menampilkan peringatan. |
| Alternative | Tidak ada |
| Post Condition | Siswa dapat login dan mengakses Sistem Alumni SMAIT Al-Ittihad |
| Exception Push | Username/email dan password salah |
   
**3.2.3 Guru BK Mengelola Data Alumni**

|  |  |
|--|--|
| Nama Fungsi | Guru bk mengelola data alumni |
| Xref | Bagian 2.2.3, Guru bk mengelola data alumnni |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data alumni |
| Basic Path | 1. Guru bk berada di halaman data alumni <br> 2. Guru bk dapat mengklik tombol edit, tambah, dan hapus <br> 3. Sistem akan menampilkan halaman formulir pengeditan jika guru bk memilih tombol edit <br> 4. Sistem akan melakukan penghapusan data alumni jika guru bk memilih tombol hapus <br> 5. Sistem akan menampilkan halaman formulir insert data alumni jika guru BK memilih tombol tambah. |
| Alternative | Tidak ada |
| Post Condition | Guru BK dapat melakukan pengelolaan terhadap data alumni. |
| Exception Push | - |
   
**3.2.4 Guru BK Mengelola Data Pengguna**

|  |  |
|--|--|
| Nama Fungsi | Guru bk mengelola data pengguna |
| Xref | Bagian 2.2.4, Guru bk mengelola data pengguna |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data user |
| Basic Path | 1. Guru BK berada di halaman data pengguna <br> 2. Guru bk dapat mengklik tombol edit, tambah, dan hapus <br> 3. Sistem akan menampilkan halaman formulir pengeditan jika guru bk memilih tombol edit <br> 4. Sistem akan melakukan penghapusan data user jika guru BK memilih tombol hapus <br> 5. Sistem akan menampilkan halaman formulir insert data user jika guru BK memilih tombol tambah. |
| Alternative | Tidak ada |
| Post Condition | Guru bk dapat melakukan pengelolaan terhadap data pengguna |
| Exception Push | - |
   
**3.2.5 Siswa Melihat Data Alumni**

|  |  |
|--|--|
| Nama Fungsi | Siswa melihat data alumni |
| Xref | Bagian 2.2.5, Siswa melihat data Alumni |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data alumni |
| Basic Path | 1. Siswa berada di halaman data alumni <br> 2. Sistem akan menampilkan halaman yang menampilkan data alumni. |
| Alternative | Tidak ada |
| Post Condition | Siswa dapat melihat data alumni berdasarkan angkatan yang dipilihnya sebelumnya |
| Exception Push | - |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada Sistem Informasi Alumni SMAIT Al-Ittihad terdapat struktur database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/ERD.jpeg)

**Tabel Guru BK**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| nip | int | berisikan nomor induk pegawai (guru) |
| username | varchar | berisikan username |
| nama | varchar | berisikan nama guru bk |
| email | varchar | berisikan email guru bk untuk mendaftar |
| password | varchar | berisikan password guru bk |

**Tabel Data Alumni**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | char | berisikan id alumni |
| nama | varchar | berisikan nama alumni |
| perguruan_tinggi | varchar | berisikan nama perguruan tinggi |
| jurusan | varchar | berisikan jurusan|
| provinsi | varchar | berisikan nama provinsi |
| jalur | varchar | berisikan nama jalur masuk perguruan tinggi |
| tahun | int | berisikan tahun tamat alumni |

**Tabel Siswa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| nis | int | berisikan nomor induk siswa |
| nama | varchar | berisikan nama siswa |
| username | varchar | berisikan username siswa |
| email | varchar | berisikan email siswa |
| password | varchar | berisikan password siswa |

**Tabel Data Pengguna**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| nip/nis | int | berisikan nomor induk |
| nama | varchar | berisikan nama pengguna |
| username | varchar | berisikan username |
| email | varchar | berisikan email pengguna |
| password | varchar | berisikan password pengguna |

**Job Desc Kel 1** <br>
Alfiya : Membuat SRS, Use case diagram <br>
Alvin : Mendesain prototype web, membuat SRS <br>
Azmi : Mengedit SRS, membuat diagram dan ERD
