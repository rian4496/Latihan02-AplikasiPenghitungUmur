# Latihan02
 Latihan02-M. Rian Gunadi-2210010497

 ![gambar](https://github.com/user-attachments/assets/89e66b3d-469e-4e65-be84-5e2d8fb25bdd)

 
# Aplikasi Penghitung Umur

Aplikasi Penghitung Umur adalah aplikasi Java Swing yang menghitung umur pengguna berdasarkan tanggal lahir yang dipilih. Selain itu, aplikasi ini menampilkan tanggal ulang tahun berikutnya serta menyediakan informasi peristiwa penting yang terjadi pada hari ulang tahun tersebut.

## Fitur

- **Hitung Umur:** Menampilkan umur pengguna berdasarkan tanggal lahir yang dipilih.
- **Ulang Tahun Berikutnya:** Menunjukkan hari dan tanggal ulang tahun pengguna berikutnya.
- **Peristiwa Penting:** Menampilkan peristiwa penting pada hari ulang tahun pengguna.

## Teknologi yang Digunakan

- Java Swing untuk tampilan antarmuka grafis
- Library `toedter.calendar` untuk memilih tanggal
- `java.time` untuk manipulasi tanggal
- Multithreading untuk mengambil data peristiwa secara asinkron

## Cara Menggunakan

1. Pilih tanggal lahir Anda menggunakan komponen `JDateChooser`.
2. Klik tombol **Hitung** untuk melihat umur Anda dan tanggal ulang tahun berikutnya.
3. Aplikasi akan menampilkan informasi peristiwa penting pada hari ulang tahun Anda berikutnya.
4. Klik **Keluar** untuk menutup aplikasi.

## Struktur Kode

- **AplikasiPenghitungUmurView** - Kelas utama yang berfungsi sebagai tampilan antarmuka utama aplikasi.
- **PenghitungUmurHelper** - Kelas pembantu yang berisi logika untuk menghitung umur, tanggal ulang tahun berikutnya, dan mengambil peristiwa penting.

## Instalasi

1. Clone atau unduh repository ini.
2. Pastikan Java Development Kit (JDK) telah terpasang.
3. Pastikan library `toedter.calendar` tersedia di dalam project Anda.
4. Buka project dengan NetBeans atau IDE lainnya, lalu jalankan aplikasi.

