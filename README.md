| Nama      | Nuryadi |
| ----------- | ----------- |
| NIM     | 312010621       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 5
Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti berikut.

disini saya menggunakan visual stusio code

![img!](lab5_javascript/img/foto1.png)

![img!](lab5_javascript/img/foto2.png)

![img!](lab5_javascript/img/foto3.png)

## 1. Javascript Dasar
Pemakaian Alert sebagai property window

![img1!](lab5_javascript/img/foto4.png)

Pemakaian method dalam objek

![img1!](lab5_javascript/img/foto5.png)

Pemakaian Prompt

![img1!](lab5_javascript/img/foto6.png)

Pembuatan fungsi dan cara pemanggilannya

![img1!](lab5_javascript/img/foto7.png)

## 2. Dasar Pemrograman Di Javascript
Operasi dasar aritmatika

![img2!](lab5_javascript/img/foto8.png)

Seleksi kondisi (if..else)

![img2!](lab5_javascript/img/foto9.png)

Penggunaan operator switch untuk seleksi kondisi

![img2!](lab5_javascript/img/foto10.png)

## 3. pembuatan Form
Form input

saya coba input nilai 8

![img3!](lab5_javascript/img/foto11.png)

Form button

![img3!](lab5_javascript/img/foto12.png)

![img3!](lab5_javascript/img/foto13.png)

## 4. HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis

![img4!](lab5_javascript/img/foto14.png)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form

## Jawab

Membuat validasi nama, no.telp, Email

## 1. Nama
Saya akan memberikan Validasi berupa inputan hanya boleh mengguankan Huruf/Alphabet saja. Contoh: Fajar (benar), Fajar02 (salah).

![imgpraktikum!](assets/img/praktikum/1-1.png)

Penjelasan
- Pertama membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai, pesan).
- Data yang boleh dimasukkan adalah berupa "a-zA-Z".
- Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/1.png)

## 2. No.Telp
Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123AB (salah).

![imgpraktikum!](assets/img/praktikum/2.png)

Penjelasan:
- var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9
- Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)
- Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/2-1.png)

## 3. Email
Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: fajar.agngn@gmail.com (benar), fajar.agngn@gmail. (salah).

![imgpraktikum!](assets/img/praktikum/3.png)

Penjelasan:
- membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/3-1.png)

## Berikut penulisan form yang benar

![imgpraktikum!](assets/img/praktikum/4.png)









