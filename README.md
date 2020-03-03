# MODUL-1-2-PHP

## Pengenalan PHP
PHP (Preprocesor Hypertext) adalah bahasa scripting yang menyatu dengan HTML dan dijalankan pada server-side. Artinya semua sintaks yang diberikan akan sepenuhnya dijalankan oleh server, sedangkan yang dikirimkan ke browser hanya hasilnya saja berupa HTML. 

## Membuat dan Menyimpan File PHP 
Cara untuk membuat dan menyimpan file PHP sama dengan cara membuat dan menyimpan file HTML. Pembuatan file PHP dilakukan dengan menggunakan aplikasi editor kode (notepad, sublime text, bracket, dll). Sedangkan cara menyimpan file PHP sedikit berbeda dengan HTML. Jika HTML disimpan menggunakan ekstensi .html maka file PHP disimpan dengan menggunakan ekstensi .php. File HTML yang didalamnya terdapat sintaks PHP meskipun hanya satu baris, file tersebut harus disimpan dengan menggunakan ekstensi .php, karena jika disimpan menggunakan .html maka sintaks PHP tersebut tidak akan diproses dan akan ditampilkan dalam web browser seperti apa adanya (berupa kode-kode). File PHP harus disimpan pada web server, disini kita akan menggunakan XAMPP, maka file harus disimpan pada direktori C:\xampp\htdocs. 

## Membuka File PHP 
Untuk membuka file PHP harus dilakukan dengan menggunakan web server. Buka web browser dan ketik http://localhost/nama_file.php . Nama file sesuai dengan nama file yang disimpan

## PHP Tipe Data
Dalam bahasa pemrograman yang lain, ada bermacam-macam tipe data, misalnya integer(bilangan bulat), float (bilangan pecahan), char(karakter angka dan huruf), string(kumpulan huruf atau kata), dan berbagai tipe lainnya.
PHP mengenal dua tipe data sederhana; numerik dan literal/string. Ditambah dengan dua tipe data yang tidak sederhana, yaitu array dan object. Tipe Numerik dapat menyimpan bilangan bulat. PHP mampu menyimpan data bilangan bulat dengan jangkauan dari -2 milyar sampai+2 milyar. Contoh bilangan bulat: 3, 7, 20. 
Selain itu, tipe numerik juga digunakan untuk menyimpan bilangan pecahan. Sedangkan tipe literal/string dapat digunakan untuk menyimpan data berupa kumpulan huruf, kata, dan angka. Tipe boolean, yang dikenal dalam bahasa program yang lainnya, tidak ada dalam PHP.
Untuk menguji benar salah (true/false), kita menggunakan tipe data yang tersedia. FALSE dapat digantikan oleh integer 0, atau string kosong, yaitu “”. Selain nilai itu, semua dianggap TRUE.

## PHP Variabel
Variabel digunakan sebagai tempat penyimpanan data sementara. Data yang disimpan dalam variabel akan hilang setelah program selesai dieksekusi. Untuk penyimpanan data yang permanen, kita dapat menyimpan data di database atau di disk.
Untuk membuat suatu variabel dalam PHP, digunakan tanda string($) sebagai pendeklarasian awal. Aturan – aturan yang dapat digunakan untuk menuliskan variabel adalah sebagai berikut :

-Pendeklarasian variabel harus ditandai dengan string ($) 

-Variabel dapat menggunakan huruf kecil maupun huruf besar atau perpaduan keduanya 

-Penulisan awal variabel tidak boleh menggunakan angka 

-Apabila ingin menggunakan angka sebagai variabelnya, maka dapat menggunakan tanda underscore() untuk memulainya 

-Nama variabel yang terdiri lebih dari satu kata, dapat dipisahkan dengan underscore ()

## Menampilkan Nilai Variabel Dengan Echo
Nilai variabel dengan mudah ditampilkan dengan menggunakan echo, baik nilai yang berupa bilangan maupun string.

### Variabel Biasa
Standar penulisan variabel adalah dengan menggunakan tanda ($) yang kemudian diikuti dengan nama variabel kemudian isi dari variabel. Dari variabel – variabel tersebut dapat dibaca berulang – ulang kali dalam satu halaman web.

### Variabel Dalam Kelompok
Bentuk variabel ini biasanya digunakan untuk mendeklarasikan data apabila menggunakan fungsi dalam PHP, isi dari data yang ada pada variabel tersebut tidak ditampilkan apabila melakukan pemanggilan fungsi yang mendeklarasikan variabel tersebut. Pemanggilan variabel di dalam sebuah fungsi menggunakan perintah global. Sedangkan untuk melakukan pemanggilan fungsi, cukup dengan memanggil nama fungsinya.

### Variabel Antar Halaman
Bentuk dari variabel ini biasanya digunakan untuk mengantarkan data yang ada dari setiap variabel ke dalam halaman lain. Bentuk – bentuk variabel ini biasanya berasal dari data seperti form.


# MODUL 1
### Latihan 1
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/1a.PNG)

### Latihan 2
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/2a.PNG)

### Latihan 3
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/3a.PNG)

### Latihan 4
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/4a.PNG)

### Latihan 5
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/5a1.PNG)
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/5a2.PNG)


# MODUL 2

Dalam bahasa pemrograman secara umum, operator digunakan untuk memanipulasi atau melakukan proses perhitungan pada suatu nilai. Operator yang akan kita pelajari adalah operator aritmatik, perbandingan, gabungan aritmatik dan assignment, serta operator logika.
operator aritmatika Digunakan untuk melakukan perhitungan matematika.
Operator perbandinganDigunakan untuk menguji hubungan antara nilai atau variabel. Operator ini digunakan dalam suatu statement bersyarat yang selalu menghasilkan nilai TRUE atau FALSE.
Gabungan Operator Aritmatika dan Asigment Operator aritmatik merupakan operasi untuk perhitungan matematika, sedangkan yang dimaksud dengan operator assignment adalah operator samadengan(=).
Operator pre/post increment dan decrement Merupakan pengembangan dari gabungan operator aritmatik dan assignment. Increment berarti peningkatan/penambahan, sedangkan decrement berarti penurunan/pengurangan. Operator ini hanya digunakan pada proses increment maupun decrement dengan tingkat 1. Artinya semua angka akan selalu dinaikkan / dikurangkan 1.Operator Logika Membandingkan dua pilihan nilai, biasanya digunakan pada struktur if – else.

### Latihan 1
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/1b.PNG)

### Latihan 2
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/2b.PNG)

### Latihan 3
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/3b.PNG)

### Latihan 4
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/4b.PNG)

### Latihan 5
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/5b.PNG)

Data diatas benar karena sesuai dengan pernyataan yaitu $f = 9 dan $k = 4

### Latihan 6
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/6b.PNG)

Data diatas benar karena terdapat tanda ||(or) apabila salah satu atau keduanya benar maka bernilai benar


## ARRAY
Array merupakan tipe data terstruktur yang berguna untuk menyimpan sejumlah data yang bertipe sama. Bagian yang menyusun array disebut elemen array. Masing-masing elemen array dapat diakses melalui index array. Index array dapat berupa biangan integer atau string.

### Latihan 7
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/7b.PNG)

Penjelasan latihan 7: Untuk mendeklarasikan atau mendefinisikan sebuah array di PHP bisa menggunakan keyword array(). Pada latihan 7, terdapat pendeklarasian dan pendefinisian array pada baris ke-3. Jumlah elemen array tidak perlu disebutkan saat deklarasi. Sedangkan untuk menampilkan isi array pada elemen tertentu, cukup dengan menyebutkan nama array beserta index array-nya (lihat baris ke-4 dan ke-5). Pendeklarasian dan pengisian array juga bisa dilakukan seperti pada baris ke-7 sampai baris ke-11. Dengan pendefinisian array seperti pada dua cara di atas, index (key) array secara otomatis akan diisi dengan bilangan bulat integer yang dimulai dari 0.

### Latihan 8
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/8b.PNG)

Penjelasan latihan 8. Untuk mendeklarasikan atau mendefinisikan sebuah array assosiatif (array yang menggunakan index selain integer), dapat dengan cara menyebutkan indexnya terlebih dahulu diikuti operator => dan diikuti value atau nilai elemennya. Sedangkan untuk menampilkan value atau nilai dari suatu array, bisa dengan menyebutkan nama array yang diikuti indexarraynya (lihat baris ke-4 dan ke-5). Pendefinisian array assosiatif juga bisa dilakukan seperti pada baris ke-7 sampai baris ke-10

### Latihan 9
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/9b.PNG)

Penjelasan latihan 9 Untuk menampilkan keseluruhan isi array bisa dilakukan dengan perulangan for, while, do..while atau foreach. Baris 5 – 7 program di atas merupakan contoh menampilkan array dengan perulangan for. Fungsi count() pada baris ke-5 berfungsi untuk mencari jumlah elemen dari array $assWarna. Untuk menampilkan array juga bisa menggunakan struktur foreach(). Struktur foreach akan mengambil elemen array mulai dari posisi pointer sampai akhir pointer. Pada contoh program di atas (baris ke-10) bisa dinyatakan dengan pernyataan bahwa “untuk setiap elemen array $arrWarna, dimasukkan ke variabel $warna”. 

### Latihan 10
![Alt Text](https://github.com/sofiaij/MODUL-1-2-PHP/blob/master/10b.PNG)

Penjelasan latihan 10 Untuk menampilkan array assosiatif bisa menggunakan perulangan foreach dan while dengan fungsi list() dan each(). Baris ke-5 dari latihan 10 di atas bisa dinyatakan dengan pernyataan “untuk setiap elemen array $arrNilai, dimasukkan key/index-nya ke variabel $nama dan masukkan value-nya ke variabel $nilai”. Pada baris ke-8 terdapat fungsi reset() yang berfungsi mengembalikan pointer array ke elemen pertama. Pada baris ke10, array assosiatif ditampilkan dengan struktur while yang menggunakan fungsi list() dan each().

# TERIMAKASIH










