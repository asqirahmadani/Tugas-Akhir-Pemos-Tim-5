# Tugas-Akhir-Pemos-Tim-5
<p>Repositori ini dibuat untuk memenuhi Tugas Akhir Praktikum Pemodelan Oseanografi 2022. Repositori ini memuat teori, metode, analisis, dan file berupa script python (py) yang dapat memproses beberapa persamaan model seperti adveksi-difusi dan hidrodinamika 1D serta 2D untuk memodelkan suatu fenomena atau dinamika oseanografi.</p>

#AUTHORS
1. Baiq Lista Azkia Sulhana_26050120120004
2. Isti'anatul Khairat_26050120120023
3. Muhamad Asqi Rahmadani_26050120130066
4. Rieke Prameswina Legendevi_26050120140085
5. Syifa Fauziah_26050120130105

# INSTALASI MINICONDA DAN LIBRARY 
1. Unduh Software pada link  [MINICONDA SOFTWARE](https://docs.conda.io/en/latest/miniconda.html#) dan pilih versi Windows dan Versi Python yang sesuaikan dengan jenis sistem operasi Windows yang digunakan.
2. File instalasi Miniconda dibuka dan pilih Run as administrator ![image](https://user-images.githubusercontent.com/105970624/169655345-fdf61fa1-d32a-4ee1-b136-723fbf1b2613.png)
3. diklik "Next" pada Dialog Instalasi Minicond ![image](https://user-images.githubusercontent.com/105970624/169655371-0bf27769-97e0-4c54-a9df-93e2ef0da71b.png)
4. diklik "I Agree" untuk Menyetujui Perjanjian Lisensi Software Miniconda ![image](https://user-images.githubusercontent.com/105970624/169655415-fe953630-b98b-476a-a4a7-89ada23757eb.png)
5. dilakukan konfigurasi Instalasi Miniconda dan pilih "allUsers" ![image](https://user-images.githubusercontent.com/105970624/169655444-83bf99bd-bb70-4d3f-8d5c-3fc06b641289.png)
6. Directory Penyimpanan Minicond dipilih ![image](https://user-images.githubusercontent.com/105970624/169655480-7a93621e-e43d-4588-a05b-f8b9c60e0071.png)
7. Opsi Tingkat Lanjut Instalasi Miniconda "Register Miniconda as the system Python 3.9" untuk memperbolehkan IDE mengakses Python Environment Miniconda. lalu diklik install ![image](https://user-images.githubusercontent.com/105970624/169655558-22471033-6e45-4e75-8f50-26ae46c874e1.png)
8. Tunggu Proses Instalasi ![image](https://user-images.githubusercontent.com/105970624/169655567-c886d0bb-aa0b-4112-8601-0d82076cf6c6.png)
9. Klik "Finish" Dialog Instalasi Miniconda ![image](https://user-images.githubusercontent.com/105970624/169655578-6e19407c-022a-4ca9-aa68-bfe7338dbd56.png)


# MODUL 1 ADVEKSI-DIFUSI 1D
# 1.1 TEORI DASAR
# 1.1.1 Adveksi 1D
*Persamaan Adveksi 
Persamaan Adveksi merupakan salah satu persamaan diferensial parsial yang memodelkan pergerakan suatu konsentrat dalam cairan yang mengalir, dengan asumsi konsentrat tersebut tidak mengalami proses difusi di dalam cairan. adveksi berkaitan erat dengan aktivitas atau pergerakan suatu benda dari suatu tempat ke tempat lainnya untuk waktu tertentu. persamaan adveksi merupakan bentuk khusus dari persamaan diferensial untuk hukum kekekalan.
  - Persamaan umum Adveksi 1D:
  
  

- Dimana :
   F : Konsentrasi zat pelarut (mg/L)
   u : Kecepatan
   x : ruang sumbu horisontal (meter)
   t : waktu (detik)
- Metode Pendekatan dalam pemodelan numerik secara umum dibagi menjadi 2 pendekatan yaitu eksplisit dan implisit. metode eksplisit dibagi menjadi 3 yaitu:
- FTCS (Forward in Time Central in Space)
  Metode FTCS merupakan gabungan dari selisih maju terhadap waktu dan selisih pusat terhadap ruang. Solusi FTCS juga termasuk ke dalam solusi stabil bersyarat.
- Syarat kestabilan:
  

- Leapfrog (CTCS)
Metode beda hingga ini merupakan perluasan dari metode beda tengah (central difference) terhadap ruang dan waktu. Skema Leapfrog didapatkan dari turunan deret taylor, ini adalah skema konsisten. Leapfrog ini akan konsisten apabila nilai C ≤1.

![image](https://user-images.githubusercontent.com/105967489/169653369-2e0b4f94-18e2-474d-bdc4-715cadc843c0.png)


- Upstream
 Metode ini menggunakan pendekatan beda maju untuk turunan waktu, sedangkan untuk turunan terhadap ruang dilakukan dengan melihat arah kecepatan u. jika > 0 maka turunan terhadap menggunakan pendejatan beda mundur. Sebaliknya jika u < 0 maka digunakan pendekatan beda maju. Stabilitas metode upstream adalah sebagai berikut:
- Jika u > 0, turunan terhadap ruang menggunakan pendekatan beda mundur.
 ![image](https://user-images.githubusercontent.com/105967489/169652264-8bd6d155-a798-45e3-9796-25bc1bd43538.png)
- Jika u < 0, turunan terhadap ruang menggunakan pendekatan beda maju.
 ![image](https://user-images.githubusercontent.com/105967489/169652271-5894b538-197d-4d27-9498-ee546a24e993.png)



# MODUL 2 ADVEKSI-DIFUSI 2D
# 2.1 TEORI DASAR
# 2.2 METODE
# 2.3 SCRIPT DAN HASIL
# 2.4 ANALISIS

# MODUL 3 HIDRODINAMIKA 1D
# 3.1 TEORI DASAR
# 3.2 METODE
# 3.3 SCRIPT DAN HASIL
# 3.4 ANALISIS

## MODUL 4 HIDRODINAMIKA 2D
### 4.1 TEORI DASAR
### 4.2 METODE
### 4.3 SCRIPT DAN HASIL
### 4.4 ANALISIS

### PENUTUP
