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

Disini menggunakan komponen <ion-header>, <ion-toolbar>, dan <ion-title>. Komponen ini digunakan untuk menampilkan judul halaman yang ditempatkan di bagian paling atas dengan font dan warna yang diinginkan.

Berikut Codenya:

![image](https://github.com/user-attachments/assets/83c8f240-8d2b-4a64-b5ec-6fab235a04b4)


**5. Menambahkan Konten Utama dengan Komponen Grid**

Tambahkan konten didalam <ion-content> lalu untuk menyusun tata letaknya digunakan komponen <ion-grid>, <ion-row>, dan <ion-col>. Komponen-komponen ini berfungsi untuk menyusun tata letak konten agar responsif di berbagai ukuran layar.

Berikut Sedikit Contoh Codenya:

<ion-content style="--background: linear-gradient(to bottom, #e0f7fa, #ffe3e8);">
  
  <ion-grid>
  
    <ion-row>
    
      <ion-col size="12">
      
        <!-- Konten lainnya -->
      
      </ion-col>
    
    </ion-row>
  
  </ion-grid>

</ion-content>


**6. Menambahkan Komponen Card untuk Profil**

Disini digunakan komponen <ion-card> lalu didalamnya ada <ion-chip> yang digunakan untuk label kecil, dan <ion-card-subtitle> untuk menampilkan teks subtitle. Komponen-komponen diatas digunakan untuk menampilkan informasi profil seperti nama dan tag lainnya dengan gaya yang lebih visual dan menarik.

Berikut Sedikit Codenya:

<ion-card style="background-color: #ffffff; border-radius: 15px; margin: 20px;">
  
  <ion-card-header style="text-align: center;">
  
    <ion-chip color="primary" outline>
    
      <ion-label>Carat's Profile</ion-label>
    
    </ion-chip>
    
    <ion-chip color="tertiary" outline>
    
      <ion-label>#HiphopUnitFan</ion-label>
    
    </ion-chip>
    
    <ion-card-subtitle style="color: #007aff; font-size: 20px;">
    
      Syifa Rahmadina
    
    </ion-card-subtitle>
  
  </ion-card-header>

</ion-card>


**7. Menambahkan Segment dan Textarea**

Disini untuk membuat pilihan tab abput, hobbies, dan fav song maka digunakan <ion-segment> lalu untuk inputannya digunakan <ion-textarea>. Komponen-komponen ini fungsinya untuk membuat tab navigasi yang mudah digunakan dan menyediakan area input untuk fans.

Berikut Sedikit Codenya:

<ion-segment value="about" mode="ios">
 
  <ion-segment-button value="about">
  
    <ion-label>About</ion-label>
  
  </ion-segment-button>
  
  <ion-segment-button value="hobbies">
  
    <ion-label>Hobbies</ion-label>
  
  </ion-segment-button>
  
  <ion-segment-button value="fav_song">
  
    <ion-label>Fav Song</ion-label>
  
  </ion-segment-button>

</ion-segment>

<ion-textarea placeholder="Share something about yourself..." rows="6" auto-grow="true">

</ion-textarea>


**8. Menambahkan Tombol Aksi**

Digunakan komponen <ion-button> untuk menambahkan tombol aksi bisa untuk submit atau melakukan aksi tertentu sesuai kehendak aplikasi. Fungsi komponen ini memungkinkan pengguna untuk mengirim informasi yang telah dimasukkan atau melakukan tindakan lain.

Berikut Sedikit Contoh Codenya:

<ion-button expand="block" color="tertiary" style="background-color: #ff4081;">

  Submit

</ion-button>


**9. Menambahkan Footer**

Disini digunakan komponen <ion-footer> yang didalamnya ada komponen <ion-toolbar> dan <ion-title> untuk menampilkan teks. Komponen-kompoen ini fungsinya untuk menampilkan informasi tambahan atau penutup dibagian baawah halaman dengan ikon dan teks.

Berikut sedikit contoh codenya:

<ion-footer>
 
  <ion-toolbar style="background-color: #ffe3e8;">
  
    <ion-title size="small" style="text-align: center; color: #007aff;">
    
      <ion-icon name="musical-notes"></ion-icon> SEVENTEEN - Circles
    
    </ion-title>
  
  </ion-toolbar>

</ion-footer>


**10. Menjalankan proyek yang telah ditambahkan komponen-komponen**

Ketikan ionic serve di terminal dan akan muncul halaman hasil dari penambahan komponen.
