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


**4. Tambahkan Kommponen Header**

Disini menggunakan komponen <ion-header>, <ion-toolbar>, dan <ion-title>. Komponen ini digunakan untuk menampilkan judul halaman yang ditempatkan di bagian paling atas dengan font dan warna yang diinginkan.

Berikut Codenya:

![image](https://github.com/user-attachments/assets/83c8f240-8d2b-4a64-b5ec-6fab235a04b4)


**5. Tambahkan Konten Utama dengan Komponen Grid**

Tambahkan konten didalam <ion-content> lalu untuk menyusun tata letaknya digunakan komponen <ion-grid>, <ion-row>, dan <ion-col>. Komponen-komponen ini berfungsi untuk menyusun tata letak konten agar responsif di berbagai ukuran layar.

Berikut Codenya:

<ion-content style="--background: linear-gradient(to bottom, #e0f7fa, #ffe3e8);">
  
  <ion-grid>
  
    <ion-row>
    
      <ion-col size="12">
      
        <!-- Konten lainnya -->
      
      </ion-col>
    
    </ion-row>
  
  </ion-grid>

</ion-content>
