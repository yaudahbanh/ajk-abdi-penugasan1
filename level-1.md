# Level 1 - Penugasan 1

1. Buat sebuah repository di GitHub. Nama repository dalam format ajk-[nama panggilan]-penugasan1. Repository ini juga sebagai tempat menaruh laporan pengerjaan untuk level selanjutnya.

Menggunakan terminal git bash dalam bentuk CLI, untuk membuat folder penugasan

![no1](src/img/level1-no1.png)

2. Implementasikan penggunaan branching yang terdiri dari master, development, featureA, dan featureB. Codebase dibebaskan

Melakukan brancing dengan urutan seperti ini

- commit master
- checkout development
- branch featureA
- commit featureA
- checkout development
- branch featureB
- commit featureB
- commit development
- checkout featureA
- merge featureB
- checkout development
- merge featureA
- checkout master
- merge development

![no2](src/img/level1-no2.png)

3. Implementasikan intruksi git untuk push, pull, stash, reset, diff, dan merge. Adanya tambahan intruksi git selain yang disebutkan akan lebih baik

Melakukan git push pada branch master ke remote