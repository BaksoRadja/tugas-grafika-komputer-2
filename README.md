# tugas-grafika-komputer-2
Tugas Grafika Komputer 2

Exercise 3.1
![WhatsApp Image 2024-03-14 at 23 22 48](https://github.com/BaksoRadja/tugas-grafika-komputer-2/assets/67650554/2c66b9f3-cf94-4105-8115-7356dddf8a50)

Exercise 3.2

 Untuk menggambar garis dengan menggunakan algoritma struktural yang dijelaskan pada
 bagian 3.3 dan 3.6, langkah-langkahnya adalah sebagai berikut:
   1. Tentukan dua titik ujung garis, yaitu (x0, y0) dan (x1, y1).
   2. Hitung nilai dx = x1- x0 dan dy = y1- y0.
   3. Hitung nilai miring rasional garis, yaitu dy/dx.
   4. Gunakan persamaan garis: y = m * x + b untuk menghitung nilai b.
   5. Mulai dari titik awal (x0, y0), lakukan langkah-langkah berikut:
     a. Hitung nilai decision variable (D) berdasarkan midpoint algorithm.
     b. Pilih piksel berikutnya yang akan digambar berdasarkan nilai D.
     c. Perbarui posisi piksel dan nilai D, dan ulangi langkah ini hingga mencapai titik akhir
       (x1, y1)
 Dengan memanfaatkan reduksi alternatif untuk piksel yang akan digambar dan menghindari
 floating point arithmetic, komputasi dapat dilakukan menggunakan operasi bilangan bulat saja.
 Jadi, untuk menggambar garis dengan menggunakan algoritma struktural pada gambar 3.6,
 langkah-langkahnya adalah menghitung nilai dx, dy, dan kemiringan garis, lalu menggunakan
 persamaan garis untuk menggambar garis dengan memilih piksel berikutnya berdasarkan nilai
 decision variable.

Exercise 3.3

![Exercise_3_3_img](https://github.com/BaksoRadja/tugas-grafika-komputer-2/assets/67650554/e3d2b641-5ca4-445b-972c-99c83a9fd7a7)
