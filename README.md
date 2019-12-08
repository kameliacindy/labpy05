## Tugas Praktikum 5

Di dalam praktikum 5 ini membahas tentang program sederhana yang akan menampilkan daftar nilai mahasiswa menggunakan Dictionary atau  `dict{}`. Di bawah ini merupakan kode-kode program yang digunakan beserta output dan penjelasannya.

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/1&2.PNG)

 - Mendeklarasikan dictionary kosong dengan nama dictionary `data = {}`
 -  Menginput salah satu menu yang tersedia **((L)ihat, (T)ambah, (U)bah, (H)apus, (C )ari, (K)eluar)** yang menggunakan perulangan **While True** 
 
  ### Menu "Tambah Data"
  
 ![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/3.PNG)
 
 Untuk menu "Tambah Data" :
 - Menggunakan inputan **t** dan menggunakan kondisi **if**
 - Melanjutkan perintah di bawahnya yaitu  menginput data (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
 - Setelah itu, akan mengakses dictionary, **nama** sebagai key dan **nama, NIM, tugas, uts, uas** sebagai value.
 - Lalu akan mencetak dictionary, setelah data diinput.
 
  ### Menu "Lihat Nilai"
  
![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/4.PNG)
 
 Untuk menu"Lihat Nilai" :
 - Menggunakan inputan **l** dan menggunakan kondisi **elif** 
 - Menggunakan kondisi **if dan else**
 - Untuk kondisi **if** apabila sebelumnya sudah melakukan input pada menu "Tambah Data" lalu akan mencetak data dalam bentuk list yang menggunakan perulangan `for x in data.values():` 
 - Tetapi, jika sebelumnya tidak melakukan input data, maka data tidak akan dicetak atau ditampilkan dan akan mencetak **TIDAK ADA DATA** yang menggunakan kondisi **else**.
 
 ### Menu "Keluar"
 
 ![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/5.PNG)
 
 Pada menu "Keluar" menggunakan inputan **k** dan fungsi pernyataan **break**, maka program akan berhenti atau keluar.
 
### Menu "Hapus Data"

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/6.PNG)

 - Menggunakan inputan **h** dan menggunakan kondisi **if dan else**
 - Menginput nama
 - Untuk kondisi **if**, kode yang digunakan `if nama in data.keys():` dan `del data[nama]` yang akan menghapus data apabila data tersebut sudah diakses.
 - Dan sebaliknya, untuk kondisi **else**, maka data tidak berhasil dihapus karena data tidak tersedia atau tidak diinput.
 
### Menu "Ubah Data"

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/7.PNG)

 - Menggunakan inputan **u** dan menggunakan kondisi **if else** 
 - Menginput nama
 - Kondisi **if** akan menginput (NIM, Nilai Tugas, Nilai UTS, Nilai UAS) yang akan diubah dan data berhasil diubah
 - Kondisi **else** apabila data belum diakses, maka data tersebut tidak dapat diubah atau data tidak ada.
 
### Menu "Cari Data"

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/8.PNG)

 - Menggunakan inputan **c** dan menggunakan kondisi **if else** 
 - Menginput nama
 - Apabila data tersebut sudah diakses, maka akan mencetak daftar nilai sesuai dengan nama yang dicari
 - Sedangkan, jika data tersebut tidak ada, maka tidak akan mencetak daftar nilai.
 
### Kondisi Else

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/9.PNG)

Perintah untuk memilih salah satu menu yang tersedia.

### Contoh Output yang dihasilkan

![enter image description here](https://github.com/kameliacindy/labpy05/blob/master/img/10.PNG)
 
