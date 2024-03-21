<div align="center">
  <h1 class="text-align: center;font-weight: bold">Praktikum 1<br>Praktek System Operasi</h1>
  <h3 class="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h3>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Dewangga Wahyu Putera Wangsa (3123500007)</strong><br>
    <strong>Hawa Kharisma Zahara (3123500010)</strong><br>
    <strong>Bayu Ariyo Vonda Wicaksono (3122500017)</strong>
  </p>

<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## Daftar Isi

1. [Pendahuluan](#pendahuluan)
2. [Soal](#proses-booting)
3. [Instalisasi](#instalisasi)
4. [Referensi](#referensi)

## PENDAHULUAN

Sistem operasi (disingkat OS) adalah perangkat lunak fundamental yang mengelola dan mengendalikan semua aspek perangkat, baik perangkat keras maupun perangkat lunak. Ia bertindak sebagai jembatan antara pengguna dan perangkat,

## PROSES BOOTING

### Apa itu booting?

Booting adalah proses yang dilakukan komputer pada saat dinyalakan hingga siap digunakan. Sebagian kita juga mengenal istilah booting sebagai proses startup komputer.

Booting berasal dari kata boot yang merupakan singkatan dari bootstrap atau bootstrapping. Bootstrap menggambarkan proses yang secara otomatis memuat dan menjalankan perintah.

Selama proses booting ini akan memuat beberapa kode ke dalam memori (RAM) yang diperlukan untuk memulai Windows sehingga siap untuk digunakan.

### Proses terjadinya Booting

![App Screenshot](assets/img/booting/booting.gif)

1. Menekan Tombol Power On
   ![App Screenshot](assets/img/booting/power-on.jpg)
   Saat Anda menyalakan komputer, daya listrik mengalir ke komponen-komponen utama, termasuk motherboard dan prosesor.

2. POST (Power-On Self-Test)
   ![App Screenshot](assets/img/booting/post.png)
   Komputer melakukan POST untuk memeriksa dan mengidentifikasi hardware utama seperti RAM, prosesor, dan kartu grafis. Jika ada masalah, komputer bisa memberikan beep atau pesan kesalahan.

3. BIOS/UEFI Initialization
   ![App Screenshot](assets/img/booting/BIOS&UEFI.png)
   BIOS (Basic Input/Output System) atau UEFI (Unified Extensible Firmware Interface) diaktifkan. Ini adalah perangkat lunak firmware yang terletak di motherboard. BIOS/UEFI memberikan instruksi awal dan menginisialisasi perangkat keras yang diperlukan.

4. Boot Loader
   ![App Screenshot](assets/img/booting/boot-priority.jpg)
   Setelah BIOS/UEFI diinisialisasi, boot loader diaktifkan. Boot loader adalah program kecil yang bertanggung jawab untuk memuat sistem operasi ke dalam memori.

5. Sistem Operasi Loading
   ![App Screenshot](assets/img/booting/loading-os.png)
   Boot loader membaca informasi tentang sistem operasi yang akan dimuat, biasanya dari partisi boot pada hard drive. Kemudian, sistem operasi dimuat ke dalam memori.

6. Kernel Initialization
   ![App Screenshot](assets/img/booting/kernel.jpg)
   Setelah sistem operasi dimuat, kernel (inti) sistem operasi diinisialisasi. Kernel bertanggung jawab untuk mengelola sumber daya komputer dan menjalankan proses-proses utama.

7. Login atau Tampilan GUI
   ![App Screenshot](assets/img/booting/lockscreen.png)
   Terakhir, sistem operasi menampilkan layar login atau antarmuka pengguna (GUI) yang memungkinkan pengguna untuk masuk dan mulai menggunakan komputer.

## Instalisasi

### A. Virtual Box

1. Pertama, silakan buka browser di PC Anda.
2. Kemudian akses situs resmi VirtualBox.
   [Virtual Box](https://www.virtualbox.org/)
   ![App Screenshot](assets/img/install_vb/0.png)
3. Kalau sudah, klik Windows host pada kolom VirtualBox 7.0.14 platform packages
   ![App Screenshot](assets/img/install_vb/01.png)
4. Tunggu proses download selesai
5. Buka File Virtual Box
   ![App Screenshot](assets/img/install_vb/02.png)
6. Selanjutnya pilih tombol Next
   ![App Screenshot](assets/img/install_vb/1.png)
   ![App Screenshot](assets/img/install_vb/2.png)
7. Maka akan muncul notifikasi Warning: Network Interfaces yang menandakan koneksi Anda akan terputus sementara
   ![App Screenshot](assets/img/install_vb/3.png)
8. Pada notifikasi ini, klik Yes untuk melanjutkan proses instalasi
   ![App Screenshot](assets/img/install_vb/4.png)
9. Klik Install untuk memulai proses pemasangan VirtualBox
   ![App Screenshot](assets/img/install_vb/5.png)
10. Tunggu sampai proses instalasi berhasil.
    ![App Screenshot](assets/img/install_vb/6.png)
11. Kalau sudah, lanjut centang opsi Start Oracle VM Virtual Box dan klik tombol Finish untuk membukanya.
    ![App Screenshot](assets/img/install_vb/7.png)
12. Selesai.

### B. Debian

1. Klik "new" untuk membuat virtual machine
   ![App Screenshot](assets/img/install_db/1.png)
2. Create virtual machine dengan mengisi nama, dan iso image. tap checklist dan next
   ![App Screenshot](assets/img/install_db/2.png)
3. Modifikasi base memory dengan ukuran 4096 Mb dan prosesor dengan ukuran 2 CPU
   ![App Screenshot](assets/img/install_db/3.png)
4. Mengubah ukuran Virtual Hard Disk menjadi 26,50 GB
   ![App Screenshot](assets/img/install_db/64.png)
5. klik Finish <br/>
   ![App Screenshot](assets/img/install_db/4.png) <br/>
6. Klik Start <br/>
   ![App Screenshot](assets/img/install_db/5.png)
7. Pilih Bahasa, disini kami memilih bahasa english <br/>
   ![App Screenshot](assets/img/install_db/6.png)
8. Konfigurasi Lokasi, **Asia** <br/>
   ![App Screenshot](assets/img/install_db/7.png)
9. Konfigurasi Lokasi, **Indonesia** <br/>
   ![App Screenshot](assets/img/install_db/8.png)
10. Konfigurasi wilayah, **United states**
    ![App Screenshot](assets/img/install_db/9.png)
11. konfigurasi Keyboard, **American English**
    ![App Screenshot](assets/img/install_db/10.png)
12. Tunggu Loading hingga selesai
    ![App Screenshot](assets/img/install_db/11.png)
13. Memasukkan Hostname
    ![App Screenshot](assets/img/install_db/12.png)
14. Kosongi domain, klik Continue
    ![App Screenshot](assets/img/install_db/14.png)
15. Setting Password
    ![App Screenshot](assets/img/install_db/15.png)
16. Memasukkan Fullname untuk setup akun
    ![App Screenshot](assets/img/install_db/16.png)
17. Memasukkan Username untuk setup akun
    ![App Screenshot](assets/img/install_db/17.png)
18. Setting Password
    ![App Screenshot](assets/img/install_db/18.png)
19. Konfigurasi Waktu, Western
    ![App Screenshot](assets/img/install_db/19.png)
20. Metode Praktisi, Manual
    ![App Screenshot](assets/img/install_db/20.png)
21. Memilih Praktisi yang ingin dimodifikasi, **ATA VBOX HARDISK**
    ![App Screenshot](assets/img/install_db/21.png)
22. Pilih Opsi **Yes**, lalu Continue
    ![App Screenshot](assets/img/install_db/22.png)
23. Pilih FREE SPACE, lalu Continue
    ![App Screenshot](assets/img/install_db/23.png)
24. Klik Create a New Partition, lalu Continue
    ![App Screenshot](assets/img/install_db/24.png)
25. Masukkan Size Partisi sebesar 20GB, lalu Continue
    ![App Screenshot](assets/img/install_db/25.png)
26. Pilih Primary, lalu Continue
    ![App Screenshot](assets/img/install_db/26.png)
27. Pilih Beginning, lalu Continue
    ![App Screenshot](assets/img/install_db/27.png)
28. Pilih Done setting up the partition, lalu Continue
    ![App Screenshot](assets/img/install_db/29.png)
29. Pilih FREE SPACE, lalu Continue
    ![App Screenshot](assets/img/install_db/30.png)
30. Klik Create a New Partition, lalu Continue
    ![App Screenshot](assets/img/install_db/31.png)
31. Masukkan Size Partisi sebesar 5GB, lalu Continue
    ![App Screenshot](assets/img/install_db/32.png)
32. Pilih Primary, lalu Continue
    ![App Screenshot](assets/img/install_db/33.png)
33. Pilih Beginning, lalu Continue
    ![App Screenshot](assets/img/install_db/34.png)
34. Klik Mount point, pilih Enter Manually
    ![App Screenshot](assets/img/install_db/35.png)
35. Ganti menjadi **/storage**
    ![App Screenshot](assets/img/install_db/41.png)
36. Klik Done setting up the partition
    ![App Screenshot](assets/img/install_db/42.png)
37. Pilih FREE SPACE, lalu Continue  
    ![App Screenshot](assets/img/install_db/36.png)
38. Klik Create a New Partition, lalu Continue
    ![App Screenshot](assets/img/install_db/37.png)
39. Masukkan Size Partisi sebesar 1.5GB, lalu Continue
    ![App Screenshot](assets/img/install_db/68.png)
40. Pilih Primary, lalu Continue
    ![App Screenshot](assets/img/install_db/38.png)
41. Pilih Beginning, lalu Continue
    ![App Screenshot](assets/img/install_db/39.png)
42. Klik use as, lalu pilih swap area
    ![App Screenshot](assets/img/install_db/65.png)
43. Klik Done setting up the partition
    ![App Screenshot](assets/img/install_db/40.png)
44. Klik Finish partitioning and write changes to disk
    ![App Screenshot](assets/img/install_db/67.png)
45. Tunggu loading install hingga selesai
    ![App Screenshot](assets/img/install_db/43.png)
46. Pilih No, lalu Continue
    ![App Screenshot](assets/img/install_db/44.png)
47. Pilih packgace manager, indonesia
    ![App Screenshot](assets/img/install_db/45.png)
48. Lalu pilih kebo.pens.ac.id
    ![App Screenshot](assets/img/install_db/46.png)
49. Http proxy dikosongkan, lalu next
    ![App Screenshot](assets/img/install_db/47.png)
50. Tunggu loading hingga selesai
    ![App Screenshot](assets/img/install_db/48.png)
51. Pilih Yes, lalu Continue
    ![App Screenshot](assets/img/install_db/49.png)
52. Checklist seperti yang tertera digambar bawah ini
    ![App Screenshot](assets/img/install_db/50.png)
53. Tunggu loading instal software
    ![App Screenshot](assets/img/install_db/51.png)
54. Pilih Yes, lalu Continue
    ![App Screenshot](assets/img/install_db/53.png)
55. Pilih sesuai dengan gambar dibawah ini
    ![App Screenshot](assets/img/install_db/54.png)
56. Finish instalisasi
    ![App Screenshot](assets/img/install_db/55.png)
57. Setelah selesai maka tampilan anda akan seperti dibawah ini, linux debian siap digunakan
    ![App Screenshot](assets/img/install_db/56.png)

## Referensi

- [Apa itu Booting](https://www.jetorbit.com/blog/mengenal-apa-itu-booting-fungsi-serta-jenis-jenis-booting/)
- [Proses Booting](https://catatanteknisi.com/pengertian-dan-urutan-proses-booting-komputer/)
- [Download Virtual Box](https://www.virtualbox.org/)
- [Download Debian](https://www.debian.org/download)
