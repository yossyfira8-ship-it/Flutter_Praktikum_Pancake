Basic Layout Flutter – Pancake

Langkah 1: Membuat main.dart
Pertama, buat file main.dart sebagai titik awal aplikasi. Di dalamnya kita mendefinisikan MaterialApp dan Scaffold untuk menyiapkan struktur dasar aplikasi.
<img width="1916" height="5810" alt="carbon (13)" src="https://github.com/user-attachments/assets/44f6e443-fa85-483c-85c0-99f9c88baeee" />

Langkah 2: Menambahkan Struktur Utama dengan Row
Agar tampilan terbagi menjadi dua sisi (teks deskripsi di kiri dan gambar di kanan), gunakan widget Row sebagai tata letak utama.

Langkah 3: Membuat Widget Deskripsi Pancake
Selanjutnya, buat widget khusus yang berisi informasi tentang Pancake.
Widget ini menampilkan:
-Judul "Pancake"
-Teks penjelasan tentang pancake
-Ikon bintang sebagai rating
-Informasi waktu persiapan, waktu memasak, dan jumlah porsi.
![1](https://github.com/user-attachments/assets/f37d1c87-6e2c-4c33-a0b4-ae6d2e740a9a)

Langkah 4: Membuat Widget Foto Pancake
Tambahkan widget untuk menampilkan gambar pancake. Pastikan gambar disimpan di folder assets/images/ dan sudah didaftarkan di pubspec.yaml.
![pancake](https://github.com/user-attachments/assets/ccf79f26-7cf2-495c-8181-3d899c4a9e19)

Langkah 5: Menggabungkan Semua Bagian
Gabungkan widget deskripsi dan widget foto ke dalam Row. Hasil akhirnya, bagian kiri menampilkan teks penjelasan pancake, sedangkan bagian kanan menampilkan gambar.
![2](https://github.com/user-attachments/assets/8919b8b2-05eb-4f0e-bf37-5f6d72793e16)
