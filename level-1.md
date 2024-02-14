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

![no3_push](src/img/level1-no3_1.png)

Melakukan git pull pada branch master, setelah ada perubahan pada file `owi.txt` pada remote

![no3_pull](src/img/level1-no3_2.png)

Melakukan stash pada branch master, karena tidak melakukan commit sebelum checkout pada branch lain

![no3_stash](src/img/level1-no3_3.png)

Melakukan git reset pada hash tertentu di file owo.txt

![no3_reset](src/img/level1-no3_4.png)

Melakukan git diff antara branch master dan branch development

![no3_diff](src/img/level1-no3_5.png)

 Melakukan git merge pada branch master dari branch development

 ![no3_merge](src/img/level1-no3_6.png)

 4. Implementasikan sebuah penanganan conflict di branch development ketika setelah merge dari branch featureA lalu merge dari branch featureB. 
Catatan: conflict bisa terjadi jika kedua branch mengerjakan di file dan line code yang sama. Buatlah skenario sendiri

Pada file `anis.txt` dilakukan perubahan yang berbeda pada content di antara branch featureA dan branch featureB. Lalu merge ke branch development

![no4_conflict](src/img/level1-no4_1.png)

![no4_resolve](src/img/level1-no4_2.png)