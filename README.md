Integrasi array dan function dalam JavaScript
Identitas Siswa
Nama: Mar'atussholiha dwi aprillia
Kelas: XI RPL 2
NIS  : 4428
Mata Pelajaran: Pemrograman Web
Deskripsi
Repository ini berisi latihan dasar penggunaan Array dan function dalam JavaScript, meliputi pembuatan Array, mengakses dan mengubah elemen, serta penggunaan properti length.

Daftar Latihan
Soal 1 — Sistem pengelolaan inventaris laboraturium komputer
Soal 2 — Pengelolaan nilai praktik siswa

Deskripsi singkat masing masing program
Soal 1 - Program mengelola array barangLab berisi keyboard, mouse, monitor, kabel HDMI. Menggunakan 4 function dengan return: tampilkanBarang untuk menampilkan + jumlah barang, tambahBarang dengan validasi kosong & duplikat, cariBarang dengan return indeks, dan hapusBarang dengan validasi tanpa mengubah data jika tidak ditemukan.
soal 2 - program untuk mengolah nilai praktik siswa menggunakan array dan function. program menampilkan daftar nilai, menghitung rata rata nilai, dan menentukan ketuntasan siswa (tuntas / belum tuntas). perhitungan rata rata dan ketuntasan menggunakan function dengan 'return'

Daftar function yang dibuat beserta kegunaannya
soal 1 :
- tampilkanBarang() - untuk menampilkan daftar barang dan jumlahnya
- tambahBarang() - untuk menambah barang baru dengan validasi kosong dan duplikat
- cariBarang() - untuk mencari barang dan mengembalikan indeksnya
- hapusBarang() - untuk menghapus barang dengan validasi jika tidak ditemukan

soal 2 :
-  tampilkanNilai() - menampilkan nilai tiap siswa
- hitungRatarata() - menghitung rata-rata nilai, return 0 jika kosong
-  hitungJumlahTuntas() - menghitung siswa tuntas >=75
-  hitungJumlahBelumTuntas() - menghitung siswa belum tuntas <75

Cara Menjalankan Program
Buka folder proyek menggunakan Visual Studio Code.
Buka Terminal.
Jalankan file JavaScript menggunakan Node.js.
Contoh:

node 01-inventaris-lab.js
Ganti nama file sesuai soal yang ingin dijalankan.

Hasil Pengujian Program

program sudah diuji menggunakan Node.js di Terminal Visual Studio Code dan berhasil berjalan tanpa error.

** Pengujian 01-inventaris-lab.js:**

=== INVENTARIS LABORATORIUM ===

daftar Barang Awal:
1. keyboard
2. mouse
3. monitor
4. kabel HDMI
jumlah barang: 4

[tambah Barang]
Webcam berhasil ditambahkan.

[cari Barang]
monitor ditemukan pada indeks -1.

[apus Barang]
Penghapusan gagal tanpa mengubah data

daftar barang terbaru:
1. keyboard
2. mouse
3. monitor
4. kabel HDMI
5. Webcam
jumlah barang: 5

=== PENGUJIAN PROGRAM ===
printer berhasil ditambahkan.
penambahan ditolak
penambahan ditolak
Cari 'Scanner': -1
Penghapusan gagal tanpa mengubah data
uji Array Kosong:
daftar barang kosong

** Pengujian 02-pengolahan-nilai.js:**

=== NILAI PRAKTIK SISWA ===
siswa 1: 60
siswa 2: 65
siswa 3: 70
siswa 4: 80
siswa 5: 90

=== REKAPITULASI ===
jumlah siswa:5
nilai rata-rata:73
jumlah tuntas:2
jumlah belum tuntas:3

Ringkasan: semua Function berjalan dengan benar, validasi data kosong, duplikat, dan tidak ditemukan berfungsi, serta perhitungan rata-rata dan jumlah tuntas sesuai dengan data.
