<div align="center">
  <h1 class="text-align: center;font-weight: bold">Praktikum 3<br>Praktek System Operasi</h1>
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

1. [PPT](#ppt)
2. [Laporan Benchmark FLOPS dan IOPS](#flops-dan-iops)
   - [Install gcc, make, dan git](#1-install-gcc-make-dan-git)
   - [Download repo dengan cara clone di GIT](#2-download-repo-dengan-cara-clone-di-git)
   - [How to Run Program FLOPS and IOPS](#3-how-to-run-program-flops-and-iops)
   - [Run program FLOPS](#4-run-program-flops)
   - [Run program IOPS](#5-run-program-iops)
   - [Tabel Pengujian](#6-tabel-pengujian)
   - [Analisa](#7-analisa)
   - [Kesimpulan](#8-kesimpulan)
3. [Referensi](#referensi)

## PPT Siklus SPU

[Link PPT](https://www.canva.com/design/DAF_FjVZneE/mGYFV4pIDyYAnDvjwu0qfg/view?utm_content=DAF_FjVZneE&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## Laporan Benchmark FlOPS dan IOPS

### 1. Install GCC, make, dan GIT

![App Screenshot](assets/img/install_gcc_make_git.jpg)

### 2. Download repo dengan cara clone di Git

![App Screenshot](assets/img/cloning.jpg)

### 3. How to Run Program FLOPS and IOPS

ketik perintah **make** pada direktory flops-iops untuk menjalankan file **makefile**

![App Screenshot](assets/img/make.jpg)

ketik perintah **make clean** untuk me-refresh file execute yang di buat dari menjalankan file **makefile**

![App Screenshot](assets/img/make_clean.jpg)

### 4. Run program FLOPS

- <strong>Run Program Pertama</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_flops1.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_f1.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_f1.png)

- <strong>Run Program Kedua</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_flops2.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_f2.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_f2.png)

- <strong>Run Program Ketiga</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_flops3.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_f3.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_f3.png)

- <strong>Run Program Keempat</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_flops4.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_f4.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_f4.png)

- <strong>Run Program Kelima</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_flops5.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_f5.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_f5.png)

### 5. Run program IOPS

- <strong>Run Program Pertama</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_iops1.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_i1.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_i1.png)

- <strong>Run Program Kedua</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_iops2.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_i2.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_i2.png)

- <strong>Run Program Ketiga</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_iops3.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_i3.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_i3.png)

- <strong>Run Program Keempat</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_iops4.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_i4.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_i4.png)

- <strong>Run Program Kelima</strong>

Hasil Run Program Dewangga Wahyu

![App Screenshot](assets/img/awang_iops5.jpg)

Hasil Run Program Hawa Kharisma

![App Screenshot](assets/img/hawa_i5.png)

Hasil Run Program Bayu Ariyo Vonda

![App Screenshot](assets/img/vonda_i5.png)

### 6. Tabel Pengujian

| Nama Anggota | Max Single Core FLOPS | Max Single Core IOPS | Max CPU FLOPS | Max CPU IOPS |
| ------------ | --------------------- | -------------------- | ------------- | ------------ |
| Awang        | 5.3                   | 5.2                  | 10.5          | 10.3         |
| Hawa         | 2.2                   | 1.9                  | 4.3           | 3.8          |
| Vonda        | 6                     | 4.5                  | 11.9          | 9            |

### 7. Analisa

Dari data yang ditunjukkan oleh table diatas menunjukkan bahwa setiap laptop dengan ketidaksamaan processor menyebabkan hasil dari test FLOPS dan IOPS berbeda-beda tergantung kecepatan dari masing-masing CPU/processor.
Mulai dari **Awang** dengan spesifikasi **Processor 11th Gen Intel(R) Core(TM) i3-1115G4 @ 3.00GHz, 2995 Mhz, 2 Core(s), 4 Logical Processor(s)**, untuk spesifikasi yang ada di debian menggunakan 2 core, bisa memperoleh angka 5.3 Gigaflops dan 5.2 Gigaiops di single core dan Max CPU berada di angka 10.5 Gigaflops dan 10.3 Gigaiops.
Lalu **Hawa** dengan spesifikasi **Processor Intel(R) Celeron(R) N4000 CPU @ 1.10GHz, 1101 Mhz, 2 Core(s), 2 Logical Processor(s)**, untuk spesifikasi yang ada di debian menggunakan 2 core, bisa memperoleh angka 4.3 Gigaflops dan 3.8 Gigaiops di single core dan Max CPU berada di angka 2.2 Gigaflops dan 1.9 Gigaiops.
lalu **vonda** dengan spesifikasi **13th Gen Intel(R) Core(TM) i5-13500H, 2600 Mhz, 12 Core(s), 16 Logical Proces**, untuk spesifikasi yang ada di debian menggunakan 2 core, bisa memperoleh angka 6 Gigaflops dan 4.5 Gigaiops di single core dan Max CPU berada di angka 11.9 Gigaflops dan 9 Gigaiops.

### 8. Kesimpulan

Dari percobaan kelompok kami, bisa ditarik kesimpulan bahwa Perbandingan antara FLOPS dan IOPS tidak langsung karena keduanya mengukur aspek yang berbeda dari kinerja sistem komputasi. FLOPS lebih berkaitan dengan kemampuan prosesor untuk melakukan perhitungan matematika, sedangkan IOPS lebih berkaitan dengan kemampuan sistem penyimpanan untuk mengakses dan memanipulasi data. Meskipun keduanya merupakan ukuran kinerja yang penting dalam konteks tertentu, mereka tidak dapat secara langsung dibandingkan atau ditukar-tukar karena masing-masing mengukur aspek yang berbeda dari kinerja sistem komputasi.

## Referensi

- [Apa itu CPU?](https://www.youtube.com/watch?v=Z5JC9Ve1sfI)
- [Siklus CPU](https://www.youtube.com/watch?v=jFDMZpkUWCw)
- [FLOPS dan IOPS](https://github.com/ferryastika/flops-iops)
