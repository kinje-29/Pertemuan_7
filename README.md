# Pertemuan 7


## Program python perulangan bertingkat

perulangan dalam bahasa pemrograman berfungsi melakukan secara berulang-ulang terdapat du jenis perulangan di python, yaitu **for** dan **While**. <br>
`for` disebut counted loop (perulangan yang terhitung)<br>
*for* biasanya digunakan untuk mengulangi code yang sudah diketahui banyak perulangan.<br>
`While` disebut uncounted loop (perulangan yang tak terhitung)<br>
*While* untuk perulangan yang memiliki syarat dan tidak tentuk berapa banyak perulangannya.



## Latihan 1
  Saya diberi Tugas untuk Buat program dengan perulangan bertingkat (nested) for.

**code**

        baris = 10
        kolom = barisan
            for i in range(baris):
              for j in range(kolom):
              hitung = i+j
        print("{0:>5}".format(hitung), end='')

     print()



**Gambar 1**<br>
Pertama kita menentukan banyak nya perulangan sebanyak 10x<br>
![01.png](/gambar1/01.png)

**Gambar 2**<br>
Variable *i* berfungsi untuk menampung indeks<br>
dan funsgi *range()* berfungsi untuk membuat list dengan range dari 1-10.<br>
![02.png](/gambar1/02.png)<br>
Fungsi **format()** berfungsi untuk melakukan pengaturan format string yang akan dicetak atau ditampilkan ke monitor.

Hasil Output<br> 
![03.png](/gambar1/03.png)<br>



## Latihan 2

Strukur algoritma latihan 2<br>

- Tampilkan n bilangan acak yang lebih kecil dari 0.5.
- nilai n diisi pada saat runtime
- anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya<br>

**Fungsi random()** <br>`Fungsi ini akan mengembalikan bilangan float random x, dimana 0 < x < 1. Fungsi random() tidak memiliki parameter masukan.`<br>

**Gambar 1**<br>
![01.png](/gambar2/01.png)<br>
Fungsi input() berfungsi untuk menerima baris input dari user dan mengembalikannya dalam bentuk string.

**Gambar 2**<br>
![02.png](/gambar2/02.png)<br>
Fungsi **format()** berfungsi untuk melakukan pengaturan format string yang akan dicetak atau ditampilkan ke monitor.

**Hasil output**<br>
![03.png](/gambar2/03.png)




