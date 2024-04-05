## Apa itu pkg dan apt ?

`pkg` dan `apt` adalah dua perintah manajemen paket yang digunakan dalam lingkungan Linux untuk mengelola instalasi, pembaruan, dan penghapusan perangkat lunak.

**pkg (Package Manager Termux):**
- `pkg` adalah manajer paket bawaan yang digunakan dalam Termux, terminal emulator untuk Android.
- Dengan menggunakan perintah `pkg`, pengguna dapat mencari, menginstal, menghapus, dan memperbarui paket perangkat lunak di Termux.
- Paket yang tersedia di Termux direpresentasikan oleh repositori resmi Termux dan repositori tambahan yang dapat ditambahkan.

**apt (Advanced Package Tool):**
- `apt` adalah perintah manajemen paket yang digunakan di banyak distribusi Linux, seperti Debian, Ubuntu, dan turunannya.
- Ini adalah salah satu alat manajemen paket yang paling umum digunakan dalam lingkungan Linux.
- Dengan menggunakan perintah `apt`, pengguna dapat menginstal, menghapus, memperbarui, dan mengelola dependensi paket perangkat lunak.
- `apt` menggunakan repositori paket Linux untuk mendapatkan informasi tentang paket yang tersedia dan mengelola instalasi perangkat lunak.

Perbedaan utama antara `pkg` dan `apt` adalah bahwa `pkg` digunakan di Termux untuk lingkungan Android, sementara `apt` digunakan di distribusi Linux seperti Debian dan Ubuntu. Meskipun keduanya memiliki fungsi yang mirip, keduanya ditujukan untuk lingkungan yang berbeda.

---

## Penggunaan `pkg` dan `apt`

Buka Aplikasi termux anda dan perbarui paketnya dengan mengetik ;
```copy
pkg update
```
setelah itu tekan `enter` dan ikuti proses pembaharuannya, jika anda menemukan tulisan seperti y/n/N? 
maka tekan y untuk melanjutkan sampai pengupdetannya selesai

setelah itu untuk mengupgrade paket maka ketik ;
```copy
pkg upgrade
```
Ikutilah proses pengupgratanya samapai selesai.
Dan jika nda ingin printah tersebut langsung keduanya dengan mengetik ;
```copy
pkg update -y && pkg upgrade -y
```
jadi variabel `-y` menyatakan yes / ya dan simbol `&&` untuk menyambung printah selanjutnya.

Jika anda menggunakan `apt` ubahlah tulisan `pkg` menjadi `apt update` dst.
