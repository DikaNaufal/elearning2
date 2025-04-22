# elearning2
TUGAS ELEARNING2 PEMROGRAMAN MOBILE
Materi Input Control pada Android Native
Saya akan memberikan penjelasan tentang Input Control di Android Native dan implementasi untuk Date Time, Alert, Toast, dan Input Phone Number. Mari kita mulai dengan penjelasan dan dilanjutkan dengan kode yang bisa dijalankan di Android Studio.
Input Control pada Android Native
Input Control adalah komponen UI yang memungkinkan pengguna memasukkan data atau berinteraksi dengan aplikasi. Android menyediakan berbagai jenis input control, seperti button, text field, checkbox, radio button, toggle button, spinner, dan lainnya.
Implementasi Input Control yang Diminta
Berikut adalah implementasi dari empat Input Control yang diminta:

Date Time: Memungkinkan pengguna memilih tanggal dan waktu dengan DatePickerDialog dan TimePickerDialog
Alert: Menampilkan pesan peringatan kepada pengguna dengan AlertDialog
Toast: Menampilkan pesan singkat yang muncul sebentar lalu hilang
Input Phone Number: Input khusus untuk nomor telepon dengan EditText dan atribut khusus

Penjelasan Implementasi
Implementasi yang saya buat mencakup 4 jenis Input Control yang diminta:
1. Date Time
Implementasi Date Time menggunakan komponen bawaan Android:

DatePickerDialog untuk memilih tanggal
TimePickerDialog untuk memilih waktu
Hasil pilihan ditampilkan di TextView

2. Alert
Implementasi Alert menggunakan AlertDialog yang dapat:

Menampilkan pesan dengan judul
Memiliki tombol positif (OK) dan negatif (Cancel)
Memberikan feedback berbentuk Toast saat tombol ditekan

3. Toast
Implementasi Toast Message menampilkan pesan singkat yang muncul dan hilang otomatis dengan:

Toast.makeText() untuk membuat Toast
Toast.LENGTH_LONG untuk durasi yang lebih lama

4. Input Phone Number
Implementasi Input Phone Number pada activity terpisah dengan:

EditText dengan inputType="phone" khusus nomor telepon
Validasi nomor telepon saat tombol ditekan
Menampilkan hasil validasi di TextView

Cara Menjalankan Proyek

Buat project baru di Android Studio dengan nama "Input Controls"
Buat package com.example.inputcontrols
Tambahkan semua file yang telah disediakan sesuai struktur folder
Build dan jalankan project pada emulator atau device fisik
