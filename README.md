# Praktikum-4

# Tugas Praktikum
Buat program sederhana untuk menambahkan data kedalam sebuah
list dengan rincian sebagai berikut:

- Progam meminta memasukkan data sebanyak-banyaknya (gunakan
  perulangan)
- Tampilkan pertanyaan untuk menambah data (y/t?), apabila jawaban
  t (Tidak), maka program akan menampilkan daftar datanya.
- Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
  uts: 35%, uas: 35%)
- Buat flowchart dan penjelasan programnya pada README.md.
- Commit dan push repository ke github.


# Membuat Program Menggunakan List pada Python


**LIST**


List adalah struktur data pada python yang mampu menyimpan lebih dari satu data, seperti array. List juga dapat kita buat seperti membuat variabel biasa, namun nilai variabelnya diisi dengan tanda kurung siku ([]) yang dapat diisi dengan tipe data apa saja, string, integer, float, double, boolean, object, dan sebagainya. Kita juga bisa mencampur isinya. Tedapat Tiga metode (method) atau fungsi yang bisa digunakan untuk menambahkan isi atau item ke List:
- prepend (item) menambahkan item dari depan;
- append (item) menambahkan item dari belakang.
- insert (index, item) menambahkan item dari indeks tertentu

Sekarang mari kita coba membuat program dengan memanfaatkan method append().

- Langkah yang pertama buka Aplikasi IDLE Python untuk membuat program di python
- Disini kita juga akan menggunakan perulangan while true agar dapat mengulangi program sebanyak-banyaknya
- Setelah itu ikuti codingan di bawah ini

<img width="960" alt="Praktikum 4" src="https://user-images.githubusercontent.com/93851727/141078140-d204bb99-b546-4637-9674-cbd91d24f668.PNG">

**BERIKUT PENJELASAN PROGRAM DIATAS**
- Variabel i, n, nm, tgs, uts, dan uas berisi [] berfungsi sebagai list yang dapat di isi dengan data apapun
- Syntax while True berfungsi agar program dapat mengulang secara terus menerus
- Setelah itu buat variabel data untuk mengisi data list
- nm.append berfungsi agar menambahkan item dari belakang dengan variabel list nm dan buat sesuai dengan variabel yang akan di tambahkan
- data = ' ' berfungsi sebagi variabel agar dapat mengulang
- while data!= 'y' and 't' berfungsi agar dapat memilih sebuah variabel
- if data == 't' break berfungsi sebagai agar jika pertanyaan t program akan berhenti
- for n in range (i) merupakan fungsi yang menghasilkan list. Fungsi ini akan menciptakan sebuah list baru dengan rentang nilai tertentu.
-  print("|",n+1," |",nm[n],"\t|\t",ni[n],"\t|", tgs[n],"\t|", uts[n],"\t|", uas[n],"\t|", akh[n]," |") agar menampilkan semua list yang sudah di input


Hasil Codingannya!!!

<img width="960" alt="Praktikum 4 Hasil" src="https://user-images.githubusercontent.com/93851727/141083046-6934341f-4179-42be-89da-4e9af216c1c0.PNG">

**SELAMAT MENCOBA, SEMOGA BERHASIL, DAN TERIMAKASIH**
