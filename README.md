# Jobjsheet-4-Sistem-Cerdas

NAMA	: Dwi Bagas Nugroho
NIM		: 5311421029
PRODI	: Teknik Eektro

Modul Praktikum 4 - TEKNIK PENCARIAN BLIND SEARCH
1.	Tentukan bagaimana algoritma BFS berikut dapat menentukan node ke 8, 6, dan 7.
Hasil :
Setealh menjalankan program praktikum maka akan mendapatkan hasil
 ![image](https://github.com/bagasnghr10/Jobjsheet-4-Sistem-Cerdas/assets/143892102/be5b1e81-781f-4c94-8872-3c9a9fdb986b)


Dalam algoritma BFS, pencarian dimulai dari simpul awal atau inisial state n3. Algoritma akan menjelajahi semua simpul yang terhubung langsung dengan simpul awal terlebih dahulu sebelum menjelajahi simpul-simpul yang lebih jauh.
•	Pada tahap pertama Dimulai dari simpul n3  akan terhubung langsung yaitu n4 dan n2. Kedua simpul ini akan ditandai sebagai "dikunjungi" algoritma akan mengunjungi simpul n4 sebelum mengunjungi simpul n2.

•	Pada tahap selanjutnya n4 akan menuju ke n5 sebagai tetangga terdekat n5 pada level 1 pencarian dan n2 akan menuju ke n6 dan n1 sebagai tetangga terdekat

•	Setelah itu, algoritma akan melanjutkan untuk mengunjungi simpul-simpul dalam antrian sesuai dengan urutan dimana n5 akan menuju ke n7 dan n6 akan menuju ke n8.

•	N8 dan n7 memiliki jarak 3 dengan simpul awal sedangkan n6 memiliki jarak 2 dengan simpul awal atau initial state

2.	Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.5 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 5.
Jawab:

Hasil: (0, d=0) (1,d=1) (2,d=1) (3,d=2) (4,d=2) (5,d=2) (6,d=2)

 ![image](https://github.com/bagasnghr10/Jobjsheet-4-Sistem-Cerdas/assets/143892102/7eb213dd-6d07-4e96-8f17-80983218123f)

 
Proses algoritma BFS dapat dijelaskan sebagai berikut:
•	Pencarian dimulai dari initial state n0.Algoritma BFS akan menelusuri semua simpul yang terhubung langsung dengan n0, yaitu n1 dan n2.
•	Selanjutnya akan mengunjungi simpul n1 dan menelusuri semua simpul yang terhubung langsung dengannya yang belum dikunjungi, yaitu n3 dan n4.
•	Algoritma akan melanjutkan proses ini sampai semua simpul yang terhubung dengan simpul awal n0 dan simpul-simpul yang telah dikunjungi telah dilalui.Dalam proses ini, algoritma akan menemukan simpul n5 karena simpul n5 terhubung langsung dengan simpul n2, yang merupakan tetangga langsung dari simpul n0.
•	Dengan demikian, melalui proses pencarian bertahap yang dilakukan oleh algoritma BFS, simpul n5 akan ditemukan setelah simpul n2 yang terhubung langsung dengan simpul n0.

3.	Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.6 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 9.
Jawab:

 
Hasil: (1,d=0) (2,d=1) (3,d=1) (4,d=1) (5,d=2) (6,d=2) (7,d=2) (8,d=2) (9,d=3) (10,d=3) (11,d=3) (12,d=3)
 ![image](https://github.com/bagasnghr10/Jobjsheet-4-Sistem-Cerdas/assets/143892102/dd9bfdc8-150d-41f6-844c-4867fadc2ca9)

Untuk menemukan node 9, proses yang dilakukan oleh algoritma BFS adalah sebagai berikut:
•	Pencarian dimulai dari simpul awal initial state adalah n1. Algoritma BFS akan menelusuri semua simpul yang terhubung langsung dengan n1, yaitu n2, n3, dan n4, dan menandainya sebagai "sudah dikunjungi”. 
•	kemudian, algoritma akan melanjutkan untuk menelusuri simpul n2, menemukan simpul-simpul yang terhubung langsung dengan n2, yaitu n5 dan n6, dan menandainya sebagai "dikunjungi". 
•	Selanjutnya, algoritma akan melanjutkan untuk menelusuri simpul-simpul yang terhubung dengan simpul-simpul yang sudah dikunjungi sebelumnya. 
•	Dalam proses ini, algoritma akan menemukan simpul n9 karena simpul n9 terhubung dengan simpul n5, yang telah dikunjungi sebelumnya yaitu n2

4.	Ubahlah kode program di atas sehingga bentuk tree seperti Gambar 4.7 Tree 3 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node C.
Jawab:

Hasil: (F,d=0) (B,d=1) (G,d=1) (A,d=2) (D,d=2) (I,d=2) (C,d=3) (E,d=3) (H,d=3)
![image](https://github.com/bagasnghr10/Jobjsheet-4-Sistem-Cerdas/assets/143892102/842e15be-9418-47e3-a3f4-be41ee8e67d6)

Untuk menemukan node C, proses yang dilakukan oleh algoritma BFS adalah sebagai berikut:
•	Pencarian dimulai dari simpul awal initial state adalah F. Algoritma BFS akan menelusuri semua simpul yang terhubung langsung dengan F, yaitu  B dan g dan menandainya sebagai simpul yang sudah dikunjungi.

•	kemudian, algoritma akan melanjutkan untuk menelusuri simpul B, menemukan simpul-simpul yang terhubung langsung dengan B, yaitu A dan D, dan menandainya sebagai "dikunjungi". 
•	kemudian, algoritma akan melanjutkan untuk menelusuri simpul G, menemukan simpul-simpul yang terhubung langsung dengan G, yaitu I dan menandainya sebagai "dikunjungi". 
•	kemudian, algoritma akan melanjutkan untuk menelusuri simpul D yang terhubung langsung dengan C dan E. 
•	Dalam proses ini, algoritma akan menemukan simpul C karena simpul C terhubung dengan simpul D ,B dan F dengan jarak 3.
 
 
