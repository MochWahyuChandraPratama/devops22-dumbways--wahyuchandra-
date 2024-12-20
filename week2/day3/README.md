# DAY 3
## VCS (Version Control System)
Sebuah alat yang gunanya untuk memanajeman perubahan suatu code. Tools yang dapat membantu developer untuk mentracking perubahan disetiap waktu. VCS pada dasarnya memiliki database terpusat yang harus terkoneksi ke jaringan bersifat online.

## GIT (Penciptanya Linus Torvalds)
Adalah salah satu tools manajemen data yang memiliki keunggulan lokasi penyimpanan tidak hanya berada dalam satu tempat. Jadi semua orang yang memiliki akses dapat terlibat dalam proyek aplikasi mulai dari pengkodean sampai menyimpan database git, sehingga dapat dimanajemen secara online maupun offline. Kenapa memilih git :
- Menyimpan seluruh versi source code.
- Memahami cara kolaborasi dalam proyek.
- Lebih aman karena tercatat siapa yang melakukan perubahan.
- Memahami cara deploy aplikasi modern.
- Ikut berkontribusi dalam proyek open source.

## Flow dari cara kerja Git
Dalam satu repository git memiliki berbagai jenis file jika akan melakukan revisi user dapat dengan mudah melakukan perubahan. File yang diubah dapat dilakukan versioning sampai final proyek. Perubahan ini akan tercatat dan terbackup secara aman, saat user ingin memanage file lama tidak akan terhapus masih bisa diakses dalam database git. Jauh lebih rapi dibandingkan penyimpanan lokal. Siapapun yang terlibat dalam proyek harus melakukan komunikasi dengan yang lain jika terjadi perubahan apapun sehingga tidak akan terjadi yang namanya error.

## Command GIT
#### Git init
Perintah git init digunakan untuk membuat project baru, lebih tepatnya fungsi git init untuk membuat repository baru. Selain itu git init juga dapat digunakan secara spesifik untuk menjadikan directory suatu project yang sedang dikerjakan menjadi repository baru digit.
```
git init
```
```
git init directory/
```
#### Git clone
Perintah git clone biasa digunakan untuk membuat clone atau salinan dari existing repo di tempat lain. Ketika melakukan git clone, repo salinan tersebut akan mempunyai log tersendiri, file sendiri, dan environtment yang berbeda dari repo aslinya.
```
git clone url_repository
```
```
git clone --branch master url_repository
```
#### Git branch
Perintah yang digunakan untuk membuat suatu versi dari repository yang ada mirip seperti clone. Fungsi branch akan digunakan untuk men-develop fitur tanpa harus mengganggu cabang utama sehingga konflik bisa dihindari.
```
git branch namabranch
```
untuk cek list branch
```
git branch -a
```
untuk menghapus branch
```
git branch -d namabranch
```
#### Git fetch
Perintah untuk mengambil semua branch dari repositori. Ini juga mengunduh semua komit dan file yang diperlukan dari repositori lain.
