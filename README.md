# p7-PPT1
Pada saat ini saya ditugaskan untuk membuat program perulangan bertingkat berikut contoh gambar yang ditugaskan <br>
![kuda](folder/kuda.png)

Pada tugas pertama, saya di minta untuk membuat program perulangan bertingkat (nested)
yang menghasilkan output seperti syntax dibawah <br>
```` python
for i in range(10) :
    for m in range(10) :
        n = i +m
        if(n<10):
            print(n, end="  ")
        else:
            print(n, end=" ")
    print()
````
Pada syntx tersebut kita membutuhkan baris dan kolom maka sebelum memasukan syntx diatas kita perlu menambahkan baris dan kolom seperti ini <br>
```` python
for i in range(10) :
    for m in range(10) :
````
Jika sudah memasukan kolom dan baris dengan menggunakan syntx diatas dan sekarang mencoba hasil membuat program perulangan bertingkat yang tugas tersebut <br>
![hasil syntax program perulangan bertingkat](folder/momo.png)
Dan sampai sini kita selesai membuat program perulangan bertingkat dan bisa melanjutkan tugas selanjut nya.
<br>
# PRAKTIKUM 1 - LATIHAN 2

![latihan 2](folder/latihan%202.png)

Tugas kedua yang di berikan oleh Dosen untuk mencari nnilai yang bernominal dibawah 0,5 Maka saya menggunakan syntx seperi berikut <br>
```` python
import random
print(40*"=")
print("Bilangan random yang lebih kecil dari 0,5")
print(40*"=")
jum = int( input("Masukan nilai n : "))
i = 0
for i in range(jum):
    i += 1
    angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
````
Syntax di atas untuk mencari bilangan random dibawah 0,5 <br>
```` python
inport random
````
Sementara untuk menentukan jumlah inputan yang diinginkan maka perlu memasukan
```` python
jum = int( input("Masukan nilai n : "))
````
Dan untuk menampilkan urutan sesua jumlah inputan dengan hasil di bawah 0,5 dengan menggunakan syntax berikut <br>
```` python
angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
````
Jika sudah selesai membuat program untuk mencari nlai random di bawah 0,5 dan sekarang kita bisa menjalankan program nya dengan gambar berikut <br>
![ret](folder/ret.png)





































