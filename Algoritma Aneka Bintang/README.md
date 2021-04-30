# Kumpulan Algoritma Bentuk Bintang dengan JavaScript
Berikut dibawah ini merupakan kumpulan algoritma bentuk-bentuk bintang dengan metode perulangan/ looping menggunakan bahasa pemrograman JavaScript
### 1. Bintang Pola Kebawah
Kode Program
```js
let rows = 5;

for (let i = 0; i < rows; i++) {
    console.log('*');
}
```
Hasil Output
```shell
*
*
*
*
*
```
### 2. Bintang Pola Kotak Persegi
Kode Program
```js
let rows = 5;
let bintangPersegi = '';

for (let i = 0; i < rows; i++) {
    for (let j = 0; j < rows; j++) {
        bintangPersegi += '*';
    }
    bintangPersegi += '\n';
}
console.log(bintangPersegi);
```
Hasil Output
```shell
*****
*****
*****
*****
*****
```
### 3. Bintang Pola Segitiga Menurun
Kode Program
```js
let rows = 5;
let segitigaKebawah = '';

for (let i = 0; i < rows3; i++) {
    for (let j = 0; j <= i; j++) {
        segitigaKebawah += '*';
    }
    segitigaKebawah += '\n';
}
console.log(segitigaKebawah);
```
Hasil Output
```shell
*
**
***
****
*****
```
### 4. Bintang Pola Segitiga Terbalik Keatas
Kode Program
```js
let rows = 5;
let segitigaKeatas = '';

for (let i = 0; i < rows4; i++) {
    for (let j = rows4; j > i; j--) {
        segitigaKeatas += '*';
    }
    segitigaKeatas += '\n';
}
console.log(segitigaKeatas);
```
Hasil Output
```shell
*****
****
***
**
*
```
