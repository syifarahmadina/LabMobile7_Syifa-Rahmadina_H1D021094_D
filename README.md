**Tugas Pertemuan 7**

**Nama: Syifa Rahmadina**

**NIM: H1D021094**


**HASIL PENAMBAHAN KOMPONEN DI HALAMAN IONIC**


![Screenshot (4151)](https://github.com/user-attachments/assets/f76078ec-e2ae-4b57-8fb3-c40b198eac18)



**Cara Menambahkan Komponen di Halaman Ionic**


**1. Mempersiapkan Proyek Ionic**

Pastikan sudah mempunyai proyek ionic dan jika belum punya buatlah dengan perintah:

ionic start nama_aplikasi

lalu pilih yang angular setelah itu sidemenu dan setelah itu pilih NgModules


**2. Akses Dokumentasi Resmi Ionic**

Buka dokumentasi ionic framework yang berisikan UI Component lalu cari komponen UI yang dibutuhkan dalam halaman yang sedang dibangun nah di dokumen ini memiliki contoh code yang bisa disalin lalu di modifikasi sesuai kebutuhan halaman yang dibangun.


**3. Buka Halaman yang Akan Diedit**

Buka proyek yang akan dikerjakan lalu buka src lalu app lalu folder dan pilih folder.page.html sebagai tempat yang akan ditambahkan komponen


**4. Menambahkan Kommponen Header**

Disini menggunakan komponen ion-header, ion-toolbar, dan ion-title. Komponen ini digunakan untuk menampilkan judul halaman yang ditempatkan di bagian paling atas dengan font dan warna yang diinginkan.

Berikut Sedikit Contoh Codenya:

![image](https://github.com/user-attachments/assets/83c8f240-8d2b-4a64-b5ec-6fab235a04b4)


**5. Menambahkan Konten Utama dengan Komponen Grid**

Tambahkan konten didalam ion-content lalu untuk menyusun tata letaknya digunakan komponen ion-grid, ion-row, dan ion-col. Komponen-komponen ini berfungsi untuk menyusun tata letak konten agar responsif di berbagai ukuran layar.

**6. Menambahkan Komponen Card untuk Profil**

Disini digunakan komponen ion-card lalu didalamnya ada ion-chip yang digunakan untuk label kecil, dan <ion-card-subtitle untuk menampilkan teks subtitle. Komponen-komponen diatas digunakan untuk menampilkan informasi profil seperti nama dan tag lainnya dengan gaya yang lebih visual dan menarik.


**7. Menambahkan Segment dan Textarea**

Disini untuk membuat pilihan tab abput, hobbies, dan fav song maka digunakan ion-segment lalu untuk inputannya digunakan ion-textarea. Komponen-komponen ini fungsinya untuk membuat tab navigasi yang mudah digunakan dan menyediakan area input untuk fans.


**8. Menambahkan Tombol Aksi**

Digunakan komponen ion-button untuk menambahkan tombol aksi bisa untuk submit atau melakukan aksi tertentu sesuai kehendak aplikasi. Fungsi komponen ini memungkinkan pengguna untuk mengirim informasi yang telah dimasukkan atau melakukan tindakan lain.


**9. Menambahkan Footer**

Disini digunakan komponen ion-footer yang didalamnya ada komponen ion-toolbar dan ion-title untuk menampilkan teks. Komponen-kompoen ini fungsinya untuk menampilkan informasi tambahan atau penutup dibagian baawah halaman dengan ikon dan teks.


**10. Menjalankan proyek yang telah ditambahkan komponen-komponen**

Ketikan ionic serve di terminal dan akan muncul halaman hasil dari penambahan komponen.
