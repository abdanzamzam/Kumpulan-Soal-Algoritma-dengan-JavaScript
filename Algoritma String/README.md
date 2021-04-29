# Kumpulan Algoritma Bermain String dengan JavaScript
Berikut dibawah ini merupakan kumpulan algoritma bermain dengan string, dimana kita akan melakukan berbagai manipulasi dengan string. Pada eksperimen ini kita akan menggunakan bahasa pemrograman JavaScript.

### 1. Membuat Segitiga String Ber-spasi
Kode Program
```js
let word = 'Hacktiv8'

for (let i = 0; i < word.length; i++) {
    let space = "";
    for (let j = 0; j < i ; j++) {
        space = space + " ";
    }
    console.log(space + word[i]);
}
```
Hasil Output
```shell
H
 a
  c
   k
    t
     i
      v
       8
```
