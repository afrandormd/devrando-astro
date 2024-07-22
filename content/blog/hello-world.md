---
external: false
draft: false
title: Variabel di javascript 
description: It's a beautiful world out there.
date: 2022-11-05
---

# Variabel
variabel adalah sesuatu yang digunakan untuk menampung nilai. variabel sendiri bisa di asumsikan sebagai wadah yang dimana kita bisa menyimpan nilai apapun di dalamnya dan wadah tersebut bisa kita beri label, agar suatu saat bisa kita panggil si variabel tersebut untuk digunakan valuenya yang nantinya bisa digunakan untuk melakukan sesuatu, atau nantinya isinya bisa di ubah.

### Aturan Penulisan Variabel
-  Nama variabel harus dimulai dengan huruf (a-z, A-Z) bisa juga menggunakan tanda dolar `$` atau garis bawah `_`.
- Mengandung huruf, angka, tanda dolar, dan garis bawah setelah karakter pertama.
- **Case-sensitive** (misal, `myVariable` dan `myvariable` berbeda).
- Tidak menggunakan kata kunci atau **reserved words** (misal, `var` `function`).

**Konvensi Penamaan:**
1. **Camel Case** digunakan untuk variabel dan fungsi.
	- Contoh: `myVariable`
1. **Pascal Case** biasanya untuk nama kelas atau constructor.
	- Contoh: `MyClass`

## String Variabel

untuk mendefinisikan variabel dapat menggunakan keyword berikut:

```javascript
var // sudah jarang digunakan lagi
let
const // tidak bisa diubah nilainya
```

**const**
sebuah keyword untuk membuat variabel di javascript yang nilainya sudah pasti dan tidak akan diubah. const perlu dideklarasikan di awal pembuatanya

contoh:
```javascript
const ayam = 10;
ayam = 15; //Error

const buah;
console.log(buah) //Error
```

contoh:
```javascript
let library = "React JS";
```
pada contoh di atas kita mendefinisikan variabel dengan nama `library` dan dengan value `React JS`

contoh variabel yang tidak diinisialisasi:
```javascript
let library;
```
Nilai default dari variabel yang tidak diinisialisasi adalah tidak terdefinisi. Ini adalah tipe data khusus yang mewakili nilai yang belum memiliki definisi.
ketika mencoba menampilkan variabel di atas menggunakan `console.log(library)` maka output yang muncul adalah `undefined`

untuk menambahkan nilai ke dalam variabel yang tidak diinisialisasi:
```javascript
let library;
library = "React JS";
```

di javascript juga dapat menetapkan nilai suatu variabel ke variabel lain. Misalnya:
```javascript
let first = "One";
let second = "Two";
second = first;
```

ketika coba di `console.log(second)` maka nilai atau isi dari variabel second adalah `one` yang dimana ini adalah isi dari variabel `first`.

## Number Variabel

untuk membuat variabel dengan nilai angka berikut contohnya:
```javascript
let count = 8;
```

dengan menggunakan tipe data angka, kita bisa melakukan operasi matematika, seperti penjumlahan, pengurangan, pembagian, perkalian dan sisa bagi (modulus)
berikut contohnya:
```javascript
let count = 8;
console.log(count + 1) // 9
console.log(count - 2) // 6
console.log(count * 3) // 24
console.log(count / 4) // 2
console.log(count % 2) // 0, (8 : 2 = sisa 0) 
```

