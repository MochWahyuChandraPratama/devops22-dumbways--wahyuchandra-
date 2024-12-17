# DAY2
### LINUX Command
#### 1. ls
Perintah untuk melihat file dan folder yang ada di penyimpanan. la juga dapat digunakan untuk melihat seluruh isi directori termasuk hidden. kombinasi dari perintah ls -la untuk melihat seluruh akses, isi directory, dan letaknya.
```
 ls /direktori/folder/path
```
```
 ls -la
```
```
 ls -R (mencantumkan semua file di subdirektori)
```
#### 2. sudo
Perintah untuk mendapatkan hak akses administrator bagi user non-root. Jika ingin masuk ke root menggunakan perintah sudo su. Perintah su memungkinkan Anda menjalankan program di shell Linux sebagai user lain.
```
 sudo (perintah)
```
```
 sudo su 
```
#### 3. pwd
Perintah untuk melihat direktori yang aktif.
```
 pwd (opsi)
```
#### 4. cd
Perintah untuk menjadikan folder home sebagai direktori.
```
 cd (nama direktori dan file yang ingin ditelusuri)
```
```
 cd .. (berpindah satu direktori ke atas)
```
#### 5. mkdir
Perintah mkdir untuk membuat satu atau beberapa direktori dan mengatur izinnya.
```
 mkdir (file) direktori/
```
```
 mkdir -v (menampilkan pesan untuk setiap direktori yang dibuat)
```
#### 6. rm
Perintah untuk menghapus file atau direktori secara permanen dalam sebuah direktori.
```
 rmdir (file) nama_direktori
```
```
 rm -i (meminta konfirmasi sebelum dihapus untuk menghindari salah hapus)
```
```
 rm file file 1
```
```
 rm -rf (mengizinkan penghapusan file/direktori tanpa konfirmasi secara rekursif)
```
#### 7. cp
Perintah untuk menyalin satu atau lebih file ke lokasi lain termasuk isinya.
```
 cp file.txt /direktori/tujuan
```
```
 cp file file1 (untuk menyalin isi dari file ke file1)
```
#### 8. mv
Perintah untuk memindahkan file dan direktori atau mengubah namanya.
 ```
 mv file /direktori/tujuan
```
```
 mv namaoldfile namanewfile
```
#### 9. touch
Perintah untuk membuat file kosong di path direktori.
```
 touch /direktori/tujuan/namafile
```
```
 touch namafile tujuan/
```
#### 10. file
Perintah untuk melihat tipe file.
```
file namafilenya
```
#### 11. zip, unzip
 Perintah zip untuk mengarsipkan file/direktori ke .zip dan perintah unzip untuk mengekstrak file/direktori yang berekstensi .zip.
```
zip archive.zip file.txt
```
```
unzip namafile.zip
```
#### 12. tar
Perintah 
