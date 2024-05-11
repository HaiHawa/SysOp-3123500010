<div align="center">
  <h1 class="text-align: center;font-weight: bold">Praktikum 9 <br>Praktek System Operasi</h1>
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

[1. Producer Consumer Semaphore](#producer-consumer-semaphore)

[2. Producer Consumer Wake-Sleep thread](#producer-consumer-wake-sleep-thread)

## Producer Consumer Semaphore

![App Screenshot](assets/img/semaphore.png)

Analisa: Program diatas contoh implementasi dari Producer Consumer Semaphore problem dalam bahasa C. Dalam kasus ini, menu yang terdapat dalam program terdapat 3 menu, yaitu pertama Producer, kedua Consumer, dan ketiga Exit. Menu pertama Producer adalah untuk membuat data dengan maximal data sebanyak 3 jika user memilih secara terus menerus tanpa memilih selain menu pertama lebih dari 3 kali maka akan mencetak pesan "Buffer your full!!" begitu juga sebaliknya jika user memilih menu kedua dan lebih dari 3 kali tanpa memilih menu selain menu kedua maka akan mencetak pesan "Buffer is empty!!". Menu ketiga untuk keluar dari program.

## Producer Consumer Wake-Sleep thread

![App Screenshot](assets/img/thread.png)

Analisa : Program diatas contoh implementasi dari Producer Consumer Semaphore problem menggunakan thread dalam bahasa C++. Dalam kasus ini, program menggunakan thread untuk menjalankan produsen dan konsumen secara bersamaan. Dengan menggunakan mekanisme seperti kunci gembok (mutex) dan lampu lalu lintas (variabel kondisi), program memastikan bahwa hanya satu proses yang dapat mengakses sumber daya pada satu waktu. Saat produsen menghasilkan sesuatu, ia memberitahu konsumen bahwa ada barang baru yang tersedia. Begitu juga ketika konsumen mengonsumsi barang, ia memberi tahu produsen bahwa ia sudah mengambil barang tersebut. Dengan demikian, program memastikan bahwa proses produksi dan konsumsi berjalan dengan aman dan terkoordinasi.

### Referensi

- [Producer Consumer Problem](https://www.geeksforgeeks.org/producer-consumer-problem-in-c/)