# Materi Intent
## Rakha Galih Nugraha S
### Pembahasan
> Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar
komponen aplikasi misal activity, services, dan broadcast receiver. 
### Ada tiga penggunaan umum intent dalam aplikasi Android yaitu:
- [x] Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- [x] Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
- [x] Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai
melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.

### Screenshot

> tampilan

![WhatsApp Image 2021-02-09 at 11 43 23 AM (1)](https://user-images.githubusercontent.com/54633534/107319581-a8584b80-6ad1-11eb-960f-fe469a81e165.jpeg)

> pemasukkan input

![WhatsApp Image 2021-02-09 at 11 43 23 AM (2)](https://user-images.githubusercontent.com/54633534/107319592-ad1cff80-6ad1-11eb-8451-85880c33e5c2.jpeg)

> pengoutputan input

![WhatsApp Image 2021-02-09 at 11 43 23 AM (3)](https://user-images.githubusercontent.com/54633534/107319605-b1491d00-6ad1-11eb-9fab-16917dcace1e.jpeg)

# Pembahasan Soal
##  perbedaan linear layout, relative layout, dan constraint layout.

### Linear Layout
> - [x] Penataan Objek menggunakan kolom dan baris yang dapat disusun secara vertikal maupun horizontal.
### Relative Layout
> - [x] Penataan Objek bersifat relatif atau bergantung kepada view yang lain. Jadi kita dapat meletakkan dimana saja mau di sisi kanan, kiri, atas, ataupun bawah dari objek lain sesuka hati kita.
### Constraint Layout
> - [x] Penataan Objek seperti pada Relative Layout. Namun, lebih fleksibel karena dapat diedit menggunakan Editor Layout pada Android Studio.

## method onCreate dan onPause pada activity.

> ![activityCycle](https://user-images.githubusercontent.com/54633534/107361786-7ca58780-6b0a-11eb-972d-d906b0ae460b.jpg)

### onCreate
> - [x] Ketika sebuah activity dibuat, pada method inilah kita melakukan inisialisasi seperti create view, list data, dan lain-lain.
### onPause
> - [x] Ketika sebuah activity lainnya dipanggil atau dimulai, method ini digunakan ketika data tidak harus disimpan kedalam system secara permanen.

### Sekian Terima Kasih :)
