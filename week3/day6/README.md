# DAY 6
## Task
1. Jelaskan apa itu Web server dan gambarkan bagaimana cara webserver bekerja.
2. Buatlah Reverse Proxy untuk aplilkasi yang sudah kalian deploy kemarin. ( dumbflix-frontend) dan implementasikan penggunaan pm2 di aplikasi tersebut, untuk domain nya sesuaikan nama masing" ex: alvin.xyz .
3. Jelaskan apa itu load balance.
4. implementasikan load balancing kepada aplikasi  dumbflix-frontend yang telah kalian gunakan.
##### Web Server
Web server adalah perangkat lunak penghubung antara client dan aplikasi yang memberi layanan berupa data atau bentuk halaman web.
- Secara garis besar, cara kerja web server adalah dengan menerima permintaan data klien, untuk kemudian mengirimnya kembali dalam bentuk berkas atau konten website.
- Ketika klien melakukan permintaan data ke web server, maka data akan tersimpan pada Transmission Control Protocol (TCP).
- Kemudian, data akan dikirim menuju ke alamat website tujuan.
- Setelah permintaan berhasil diproses, maka browser akan menampilkan data server dalam bentuk halaman, konten website atau berkas yang tampil di layar monitor Anda.
- Namun, jika request data tidak dapat ditemukan, maka otomatis web server akan menolak permintaan tersebut dan menampilkan notifikasi “Page Not Found” atau “Error 404”.
#### Reverse Proxy

#### Load Balance
Load balance adalah suatu konfigurasi sebagai respon antisipasi jika sewaktu-waktu terjadi kendala pada salah satu server akan ada backup server. Biasanya menggunkan algoritma Round Robin, metode ini bekerja dengan cara menyalurkan lalu lintas jaringan secara berurutan dari satu server ke server lainnya sehingga menciptakan rotasi pembagian yang stabil.
#### Implementasi Load Balancing
