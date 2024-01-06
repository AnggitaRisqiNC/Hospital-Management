# Hospital Management

## Anggota Kelompok <br>

| Nama                      | NIM       | Kelas     | Mata Kuliah                 |
| ------------------------- | --------- | --------- | --------------------------- |
| Anggita Risqi Nur Clarita | 312210450 | TI.22.A.4 | Object Oriented Programming |
| Faizah Via Fadhillah      | 312210460 | TI.22.A.4 | Object Oriented Programming |
| Liskania Aprilia          | 312210383 | TI.22.A.4 | Object Oriented Programming |
| Zahra Nurhaliza           | 312210364 | TI.22.A.4 | Object Oriented Programming |

## Daftar Isi <br>

| No  | Description             | Link                                                    |
| --- | ----------------------- | ------------------------------------------------------- |
| 1   | Introduction            | [Click Here](#introduction)                             |
| 2   | Fitur-Fitur Website     | [Click Here](#website-ini-memiliki-fitur-fitur-berikut) |
| 3   | Which Is Use            | [Click Here](#which-is-used)                            |
| 4   | How To Run This Project | [Click Here](#how-to-run-this-project)                  |

### Introduction

**Website hospital management adalah sebuah sistem informasi yang dirancang untuk membantu mengelola operasional rumah sakit.** Sistem ini dapat digunakan untuk mengelola berbagai aspek operasional rumah sakit, mulai dari pendaftaran pasien, pengelolaan jadwal dokter, hingga penagihan biaya perawatan.

Website hospital management yang dibuat dengan **Python**, **Django**, dan **sqlite** memiliki beberapa kelebihan, antara lain:

- Kode yang lebih mudah dibaca dan dipahami

- Lebih cepat dan efisien

- Dapat diintegrasikan dengan berbagai sistem lain

Website ini menggunakan database **db.sqlite3** yang merupakan database bawaan Python. Database ini mudah untuk digunakan dan dikelola, sehingga cocok untuk aplikasi dengan skala kecil dan menengah.

### Website ini memiliki fitur-fitur berikut:

#### Admin

- Admin dapat mendaftarkan akun mereka sendiri tanpa persetujuan dari pihak lain. Setelah akun berhasil dibuat, admin dapat melakukan login untuk mengakses sistem.

- Admin dapat mendaftarkan, melihat, menyetujui, menolak dan menghapus dokter (menyetujui dokter yang melamar pekerjaan di rumah sakit mereka).

- Admin dapat menerima, melihat, menyetujui, menolak dan memulangkan pasien (memulangkan pasien setelah perawatan selesai).

- Admin dapat membuat dan mengunduh Invoice pdf (Membuat Invoice sesuai dengan biaya obat, biaya kamar, biaya dokter dan biaya lainnya).

- Admin dapat melihat, memesan dan menyetujui janji temu (menyetujui janji temu yang diminta oleh pasien). Kewenangan ini diperlukan untuk mengelola jadwal dokter dan pasien.

#### Doctor

- Dokter harus melamar pekerjaan di rumah sakit terlebih dahulu sebelum dapat bekerja di sana. Lamaran pekerjaan tersebut akan disetujui atau ditolak oleh admin. Setelah disetujui, dokter dapat melakukan login untuk mengakses sistem.

- Dokter hanya dapat melihat detail pasien yang ditugaskan kepada mereka oleh admin. Detail tersebut meliputi gejala, nama, dan nomor telepon pasien.

- Dokter dapat melihat daftar pasien yang telah dipulangkan oleh admin. Daftar ini dapat digunakan oleh dokter untuk mengetahui status pasien yang telah mereka tangani.

- Dokter dapat melihat janji temu mereka yang telah dipesan oleh admin. Dokter dapat membatalkan janji temu tersebut jika diperlukan.

- Dokter dapat menghapus janji temu mereka setelah menghadiri janji temu tersebut. Hal ini dilakukan untuk menandakan bahwa janji temu tersebut telah selesai.

#### Patient

- Pasien harus membuat akun terlebih dahulu sebelum dapat masuk ke rumah sakit. Akun ini akan disetujui atau ditolak oleh admin. Setelah disetujui, pasien dapat melakukan login untuk mengakses sistem.

- Pasien dapat melihat detail dokter yang ditugaskan kepada mereka. Detail tersebut meliputi spesialisasi, nomor telepon, dan alamat dokter.

- Pasien dapat melihat status janji temu yang telah mereka pesan. Status tersebut meliputi tertunda atau dikonfirmasi oleh admin.

- Pasien dapat membuat janji temu dengan dokter. Namun, janji temu tersebut harus disetujui oleh admin terlebih dahulu.

- Pasien dapat melihat atau mengunduh faktur PDF setelah mereka dipulangkan oleh admin. Faktur ini berisi informasi tentang biaya perawatan pasien.

### Which Is Used

1. **Django**

   Django adalah sebuah framework web yang ditulis dengan bahasa Python. Framework ini menyediakan berbagai fitur yang dapat memudahkan pengembangan web, seperti: routing, model, view dan template.

   Dalam sistem hospital management, Django digunakan untuk membuat struktur aplikasi web, membuat model database, dan menangani permintaan dari pengguna.

2. **Python**

   Python adalah bahasa pemrograman tingkat tinggi yang bersifat interpretatif dan general purpose. Dalam sistem hospital management, Python digunakan sebagai bahasa pemrograman utama untuk membuat aplikasi web.

3. **SQLite**

   SQLite adalah database relasional yang ringan dan mudah digunakan. Database ini merupakan database bawaan Python, sehingga dapat digunakan tanpa perlu menginstal software tambahan.

   Dalam sistem manajemen hospital, SQLite digunakan sebagai database untuk menyimpan data pengguna, jadwal dokter, pasien, biaya perawatan, dan janji temu.

4. **VSCode**

   Untuk editor kode, kami menggunakan Visual Studio Code (VSCode). VSCode adalah editor kode sumber yang populer yang dapat digunakan untuk berbagai bahasa pemrograman. VSCode memiliki fitur-fitur yang memudahkan pengembang untuk menulis, mengedit, dan menjalankan kode.

5. **Bootstrap**

   Untuk membuat tampilan halaman web, kami menggunakan Bootstrap. Bootstrap adalah framework CSS yang populer yang dapat digunakan untuk membuat tampilan halaman web yang responsif. Bootstrap memiliki fitur-fitur yang memudahkan pengembang untuk membuat tampilan halaman web yang menarik dan mudah digunakan.

## How To Run This Project?

1. **Instalasi Python**

   Unduh Python dari situs resminya: https://www.python.org/downloads/

   Saat instalasi, pastikan untuk mencentang kotak "Add Python to PATH". Ini akan memudahkan Anda menjalankan Python melalui perintah di terminal.

2. **Mengunduh dan menyiapkan proyek**

   ```
   https://github.com/AnggitaRisqiNC/Hospital-Management.git
   ```

   Silahkan clone repository ini atau download ZIP kemudian extract file ZIP tersebut ke sebuah folder.

3. **Pemasangan paket-paket**

   Buka terminal atau command prompt Anda.

   Ketik perintah berikut satu per satu untuk memasang paket-paket yang dibutuhkan:

   ```
   pip install django-widget-tweaks
   pip install xhtml2pdf
   ```

4. **Menyiapkan database**

   Jalankan perintah berikut untuk menyiapkan database:

   ```
   py manage.py makemigrations
   py manage.py migrate
   ```

5. **Menjalankan server**

   Jalankan perintah berikut untuk memulai server:

   ```
   py manage.py runserver
   ```

6. **Mengakses project di browser**

   Buka browser di komputer Anda (misalnya, Chrome, Firefox, Edge).

   Masukkan alamat berikut di address bar browser:

   http://127.0.0.1:8000/

   Anda seharusnya akan melihat tampilan project Django yang sudah berjalan.

## Finish

<img align="left" width="150" height="150" src="https://octodex.github.com/images/ironcat.jpg"></a>

Terima kasih telah meluangkan waktu untuk membaca penjelasan mengenai project UAS Object Oriented Programming kami hingga akhir tentang Sistem Hospital Management.

Kami harap penjelasan ini dapat memberikan gambaran yang jelas tentang fitur-fitur yang tersedia di website Hospital Management.

~ _**Kelompok 11**_
