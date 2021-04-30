# Kumpulan Soal Algoritma Berdasarkan Studi Kasus
Berikut dibawah ini merupakan kumpulan algoritma dalam implementasi studi kasus sederhana. Hal ini untuk melatih pondasi kemampuan kita terhadap logika dan bahasa pemrograman.
### 1. Bintang Pola Kebawah
**Kode Program**
```js
let rows = 5;

for (let i = 0; i < rows; i++) {
    console.log('*');
}
```
**Hasil Output**
```shell
*
*
*
*
*
```
### 2. Bintang Pola Kotak Persegi
**Kode Program**
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
**Hasil Output**
```shell
*****
*****
*****
*****
*****
```
### 3. Bintang Pola Segitiga Menurun
### 4. Bintang Pola Segitiga Menurun Terbalik
