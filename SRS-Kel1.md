<p align="center">
<img src="https://github.com/azmifa/ProjekFramework/blob/main/Cover%20SRS.jpeg" width="595" height="834"/ >
</p>

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
Pada zaman era globalisasi perkembangan teknologi begitu sangat pesat, salah satunya ialah perkembangan teknologi di bidang software engineering dimana software engineering dapat digunakan dalam kehidupan sehari - hari. Dalam studi kasus ini kami menganalisis kebutuhan suatu sekolah di daerah Pekanbaru, Riau tepatnya di kecamatan Rumbai. Kasus yang kami peroleh yaitu perancangan Sistem Informasi Alumni. Maka dari itu kami sebagai software developer merancang sebuah sistem sesuai dengan kebutuhan SMA Al-Ittihad dengan menerapkan Sistem Informasi yang dapat melakukan pencatatan terhadap data alumni sehingga memudahkan guru bk dalam menginputkan data-data alumni dan pengguna dapat melihat data yang sudah diinputkan. Software yang kami buat ini adalah berbasis website dimana sistem ini digunakan untuk guru BK (admin) dan juga pengguna. Berikut merupakan fungsi pada admin yaitu :
   - Mengelola siswa
   - Mengelola perkuliahan alumni
   - Mengelola pekerjaan alumni
   - Mengelola lowongan pekerjaan
   - Mengelola guru
   - Mengelola pengguna
     
   Berikut ini fungsi pengguna :
   - View siswa
   - View perkuliahan alumni
   - View pekerjaan alumni
   - View lowongan pekerjaan
   - View guru

2.1   Perspektif produk
----------
Sistem Informasi Alumni SMAIT Al-Ittihad adalah sebuah sistem administrasi data yang diaplikasikan pada website. Terdapat 2 jenis yaitu guru BK dan pengguna. Pengolahan data di kelola oleh guru BK dan pengguna hanya dapat melihat informasi pada website.

Pada sistem informasi alumni ini akan menampilkan data alumni yang sudah diinputkan oleh guru BK.

**2.1.1 Antarmuka Sistem**

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/01ef504a6b5f71838cb72f2d12e946769f018358/Diagram/UseCaseSistem.png)

Sistem informasi alumni ini memiliki 2 user yaitu guru BK dan pengguna. Pengguna mempunyai fungsi yaitu melakukan view data alumni. Guru BK bertugas untuk mengelola data, supaya data bisa di akses oleh pengguna.

**2.1.2 Antarmuka Pengguna**

**Mockup Guru BK (Website)**

|  |  |
|--|--|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/4f20f7078b16d20a7f013d147998c7eb0f9cc87c/Prototype-GuruBK/HalamanLogin.png) Pada halaman login admin diminta untuk mengisi username dan password.| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanBeranda.png) Pada halaman ini nantinya akan ditampilkan beberapa informasi seperti jumlah siswa, perkuliahan alumni, alumni yang bekerja, loker, dan guru.|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanSiswa.png) Pada halaman ini akan ditampilkan data siswa | ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanPerkuliahanAlumni.png) Pada halaman ini akan ditampilkan data perkuliahan alumni|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanPekerjaanAlumni.png) Pada halaman ini akan ditampilkan data pekerjaan alumni| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanLowonganPekerjaan.png) Pada Halaman ini akan ditampilkan lowongan pekerjaan yang tersedia|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanGuru.png) Halaman ini akan ditampilkan data guru| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/2941da396bb533a231799863cc149a121dcc28b8/Prototype-GuruBK/HalamanPengguna.png) Halaman ini akan ditampilkan data pengguna| |

 **Mockup Pengguna (Website)**

|  |  |
|--|--|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/384732d16eeebfadc088cf4fe98b466104ffe723/Prototype-Pengguna/HalamanBeranda.png) Pada halaman beranda, pengguna dapat melihat beberapa informasi seperti perkuliahan alumni, alumni yang bekerja, loker, dan guru.| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/384732d16eeebfadc088cf4fe98b466104ffe723/Prototype-Pengguna/HalamanPerkuliahanAlumni.png) Pada halaman ini nantinya akan ditampilkan data perkuliahan alumni.|
| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/384732d16eeebfadc088cf4fe98b466104ffe723/Prototype-Pengguna/HalamanPekerjaanAlumni.png) Pada halaman ini akan ditampilkan data pekerjaan alumni.| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/384732d16eeebfadc088cf4fe98b466104ffe723/Prototype-Pengguna/HalamanGuru.png) Pada halaman ini nantinya akan ditampilkan data guru.| ![enter image description here](https://github.com/azmifa/ProjekFramework/blob/384732d16eeebfadc088cf4fe98b466104ffe723/Prototype-Pengguna/HalamanLoker.png) Pada halaman ini nantinya akan ditampilkan lowongan pekerjaan yang tersedia.| | |

**2.1.3 Antarmuka Perangkat Keras**

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/Diagram.jpeg)

Antarmuka perangkat keras yang digunakan untuk mengoperasikan Perangkat Lunak Sistem Alumni SMAIT Al-Ittihad antara lain :

1. PC / Laptop
Untuk menjalankan Aplikasi ini admin membutuhkan sebuah PC yang menggunakan OS Windows, Linux, atau MAC dan sudah terinstall browser .

**2.1.4 Antarmuka Perangkat Lunak**

Tidak ada

**2.1.5 Antarmuka Komunikasi**

Antarmuka komunikasi yang digunakan untuk mengoperasikan perangkat lunak Sistem Informasi Alumni SMAIT Al-Ittihad antara lain :
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
![](https://github.com/azmifa/ProjekFramework/blob/01ef504a6b5f71838cb72f2d12e946769f018358/Diagram/UseCaseManajemen.png)
   
**2.2.1 Guru BK Masuk Ke Sistem**

Use Case: Guru BK masuk ke sistem

Diagram : 
![](https://github.com/azmifa/ProjekFramework/blob/cd69e7461ad694c81e749a362fe3fe1a6e36d8a5/Diagram/UseCaseGuruBKMasuk.png)

Deskripsi singkat :
Guru BK membuat akun terlebih dahulu agar dapat masuk ke sistem.

Deskripsi langkah-langkah :
1. Guru masuk ke sistem dengan username dan password
2. Sistem melakukan validasi masuk sistem
3. Bila sukses sistem akan mengarahkan ke halaman beranda
4. Bila gagal sistem akan menampilkan peringatan

Xref: Bagian 3.2.1, Guru BK masuk ke sistem
   
**2.2.2 Pengguna Masuk Ke Sistem**

Use Case: Pengguna masuk ke sistem

Diagram: 
![](https://github.com/azmifa/ProjekFramework/blob/cd69e7461ad694c81e749a362fe3fe1a6e36d8a5/Diagram/UseCasePenggunaMasuk.png)

Deskripsi singkat :
Pengguna langsung masuk ke sistem tanpa mengisi form login.

Deskripsi langkah-langkah :
1. Pengguna masuk ke sistem tanpa melakukan login
2. Sistem akan mengarahkan ke halaman beranda

Xref: Bagian 3.2.2, Pengguna masuk ke sistem

**2.2.3 Guru BK Mengelola Data Alumni**

Use Case: Guru BK mengelola data alumni

Diagram :
![](https://github.com/azmifa/ProjekFramework/blob/cd69e7461ad694c81e749a362fe3fe1a6e36d8a5/Diagram/UseCaseGuruBKMengelolaData.png)

Deskripsi singkat :
Guru BK dapat mengelola data alumni.

Deskripsi langkah-langkah :
1. Sistem menampilkan data Alumni
2. Guru BK dapat memilih tombol tambah data, edit, dan hapus untuk melakukan pengelolaan data
3. Sistem akan menampilkan data alumni terbaru jika guru BK melakukan pengubahan data.

Xref: Bagian 3.2.3, Guru BK mengelola data alumni
      
**2.2.4 Guru BK Mengelola Data Pengguna**

Use Case: Guru BK mengelola data pengguna

Diagram:
![](https://github.com/azmifa/ProjekFramework/blob/cd69e7461ad694c81e749a362fe3fe1a6e36d8a5/Diagram/UseCaseGuruBKMengelolaPengguna.png)
      
Deskripsi singkat :
Sistem akan menampilkan tabel pengguna dan guru BK dapat menambah dan mengedit pengguna sesuai kebutuhan.

Deskripsi langkah-langkah :
1. Guru BK mengklik menu data pengguna, lalu guru BK dapat memilih tombol tambah, edit, dan hapus untuk melakukan pengelolaan terhadap data pengguna.
2. Sistem akan menyimpan data pengguna ke database dan menampilkan data pengguna yang dipilih.
3. Guru BK bisa menghapus hak akses pengguna.

Xref: Bagian 3.2.4, Mengelola data pengguna

**2.2.5 Pengguna Melihat Data Alumni**

Use Case: Melihat data alumni

Diagram:
![](https://github.com/azmifa/ProjekFramework/blob/cd69e7461ad694c81e749a362fe3fe1a6e36d8a5/Diagram/UseCasePenggunaMelihatDataAlumni.png)

Deskripsi singkat :
Sistem akan menampilkan data alumni dan pengguna dapat melihat data alumni.

Deskripsi langkah-langkah :
1. Pengguna berhasil melakukan login
2. Sistem menampilkan halaman beranda yang berisi data alumni.

Xref: Bagian 3.2.5, Melihat data alumni
   
2.3   Spesifikasi Kebutuhan Non-Fungsional
----------
- Tabel Kebutuhan Non-Fungsional 

   | No | Deskripsi |
   | ------ | ------ |
   | 1 | Semua interface dan fungsi menggunakan Bahasa Indonesia |
   | 2 | Perangkat lunak dapat dipakai di semua platofrm  OS ( guru BK dan pengguna) 
 
2.4   Karakteristik Pengguna
----------
Karakteristik pengguna dari perangkat lunak ini adalah pengguna langsung berinteraksi dengan sistem tanpa harus dihubungkan dengan hak akses atau level autentikasi.

2.5   Batasan-Batasan
----------
- Perangkat lunak web hanya dijalankan di windows (7,8,10). 
- Waktu pengembangan perangkat lunak yang singkat membuat adanya kemungkinan tidak semua fungsi yang ada dapat dilaksanakan.

2.6   Asumsi-Asumsi
----------
Maksimal penginputan id atau memasukkan kode pada aplikasi ini adalah 9999, lebih dari itu program akan muncul peringatan "Anda telah melebihi batas maksimum".

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
      
**3.2.1 Guru BK Masuk Ke Sistem**

|  |  |
|--|--|
| Nama Fungsi | Guru BK masuk ke sistem |
| Xref | Bagian 2.2.1, Guru BK masuk ke sistem |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman masuk |
| Basic Path | 1. Guru bk mengisi form masuk dengan username dan password <br> 2. Guru bk mengklik tombol login <br> 3. Sistem melakukan validasi masuk <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5. Bila gagal sistem akan menampilkan peringatan |
| Alternative | Tidak ada |
| Post Condition | Guru BK dapat masuk ke sistem dan mengakses Sistem Alumni SMAIT Al-Ittihad |
| Exception Push | Username dan password salah |
      
**3.2.2 Pengguna Masuk Ke Sistem**

|  |  |
|--|--|
| Nama Fungsi | Pengguna masuk ke sistem |
| Xref | Bagian 2.2.2, Siswa masuk ke sistem |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman masuk |
| Basic Path | 1. Pengguna mengisi form login dengan username/email dan password <br> 2. Pengguna mengklik tombol login <br> 3. Sistem melakukan validasi login <br> 4. Bila sukses sistem akan mengarahkan ke halaman beranda <br> 5.Bila gagal sistem akan menampilkan peringatan. |
| Alternative | Tidak ada |
| Post Condition | Pengguna dapat login dan mengakses Sistem Alumni SMAIT Al-Ittihad |
| Exception Push | Username/email dan password salah |
   
**3.2.3 Guru BK Mengelola Data Alumni**

|  |  |
|--|--|
| Nama Fungsi | Guru BK mengelola data alumni |
| Xref | Bagian 2.2.3, Guru bk mengelola data alumnni |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data alumni |
| Basic Path | 1. Guru BK berada di halaman data alumni <br> 2. Guru BK dapat mengklik tombol edit, tambah, dan hapus <br> 3. Sistem akan menampilkan halaman formulir pengeditan jika guru BK memilih tombol edit <br> 4. Sistem akan melakukan penghapusan data alumni jika guru BK memilih tombol hapus <br> 5. Sistem akan menampilkan halaman formulir insert data alumni jika guru BK memilih tombol tambah. |
| Alternative | Tidak ada |
| Post Condition | Guru BK dapat melakukan pengelolaan terhadap data alumni. |
| Exception Push | - |
   
**3.2.4 Guru BK Mengelola Data Pengguna**

|  |  |
|--|--|
| Nama Fungsi | Guru BK mengelola data pengguna |
| Xref | Bagian 2.2.4, Guru BK mengelola data pengguna |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data pengguna |
| Basic Path | 1. Guru BK berada di halaman data pengguna <br> 2. Guru BK dapat mengklik tombol edit, tambah, dan hapus <br> 3. Sistem akan menampilkan halaman formulir pengeditan jika guru BK memilih tombol edit <br> 4. Sistem akan melakukan penghapusan data pengguna jika guru BK memilih tombol hapus <br> 5. Sistem akan menampilkan halaman formulir insert data user jika guru BK memilih tombol tambah. |
| Alternative | Tidak ada |
| Post Condition | Guru BK dapat melakukan pengelolaan terhadap data pengguna |
| Exception Push | - |
   
**3.2.5 Pengguna Melihat Data Alumni**

|  |  |
|--|--|
| Nama Fungsi | Pengguna melihat data alumni |
| Xref | Bagian 2.2.5, Pengguna melihat data Alumni |
| Trigger | Membuka website Sistem Alumni SMAIT Al-Ittihad |
| Precondition | Halaman data alumni |
| Basic Path | 1. Pengguna berada di halaman data alumni <br> 2. Sistem akan menampilkan halaman yang menampilkan data alumni. |
| Alternative | Tidak ada |
| Post Condition | Pengguna dapat melihat data alumni berdasarkan angkatan yang dipilihnya sebelumnya |
| Exception Push | - |
   
3.3 Struktur Detail Kebutuhan Non-Fungsional
----------
**3.3.1 Logika Struktur Data**
Struktur data logika pada Sistem Informasi Alumni SMAIT Al-Ittihad terdapat struktur database yang dijelaskan menggunakan ERD.

![enter image description here](https://github.com/azmifa/ProjekFramework/blob/main/Diagram/ERD.jpeg)

**Tabel Data Siswa**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id siswa |
| nama | varchar | berisikan nama siswa |
| foto | varchar | berisikan foto siswa |
| nim | varchar | berisikan nim siswa |
| angkatan | int | berisikan angkatan siswa |
| kelas | varchar | berisikan kelas siswa |
| jurusan | varchar | berisikan jurusan siswa |

**Tabel Data Perkuliahan Alumni**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id perkuliahan alumni |
| nama | varchar | berisikan nama alumni |
| foto | varchar | berisikan foto alumni |
| angkatan | int | berisikan angkatan alumni |
| perguruan_tinggi | varchar | berisikan nama perguruan tinggi |
| kategori | varchar | berisikan kategori |
| jurusan | varchar | berisikan jurusan |
| provinsi | varchar | berisikan nama provinsi |
| jalur | varchar | berisikan nama jalur masuk perguruan tinggi |
| tahun | int | berisikan tahun tamat alumni |

**Tabel Data Pekerjaan Alumni**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id pekerjaan alumni |
| nama | varchar | berisikan nama alumni |
| foto | varchar | berisikan foto alumni |
| angkatan | int | berisikan angkatan alumni |
| tempat_kerja | varchar | berisikan tempat kerja alumni |
| jabatan | varchar | berisikan jabatan alumni |

**Tabel Data Lowongan Pekerjaan**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id lowongan pekerjaan |
| nama_perusahaan | varchar | berisikan nama perusahaan |
| nama_pekerjaan | varchar | berisikan nama pekerjaan |
| posisi_pekerjaan | varchar | berisikan posisi pekerjaan |
| kontak | varchar | berisikan kontak |
| tanggal_pendaftaran | date | berisikan tanggal pendaftaran |
| tanggal_penutupan | date | berisikan tanggal penutupan |

**Tabel Data Guru**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id guru |
| nama | varchar | berisikan nama guru |
| foto | varchar | berisikan foto guru |
| email | varchar | berisikan email guru |
| deskripsi | text | berisikan deskripsi |

**Tabel Data User**

| Data Item | Type | Deskripsi |
| ------ | ------ | ------ |
| id | varchar | berisikan id pengguna |
| nama | varchar | berisikan nama pengguna |
| username | varchar | berisikan username |
| email | varchar | berisikan email pengguna untuk mendaftar |
| password | varchar | berisikan password pengguna |

**Job Desc Kel 1** <br>
Alfiya : Membuat SRS, Use case diagram <br>
Alvin : Mendesain prototype web, membuat SRS <br>
Azmi : Mengedit SRS, membuat diagram dan ERD

**Dokumentasi** <br>
<p align="center">
<img src="https://github.com/azmifa/ProjekFramework/blob/main/Dokumentasi%20Kel%201.png" width="720" height="520"/ >
</p>
