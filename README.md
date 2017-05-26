# TAPBO
<h1>Cara Menampilkan Data dari ComboBox ke TextField Tanpa Button (NetBeans)</h1>
<h3>Buka Netbeans IDE 8.1, kemudian  klik new Project dan pilih Java Application</h3>
![1](https://github.com/religins/TAPBO/blob/master/1.JPG)
![1b](https://github.com/religins/TAPBO/blob/master/2.JPG)

<h3>Buat Project baru dengan nama apa saja, untuk tutorial ini saya menggunakan ReligiNS_CBtoTF</h3>
![2](https://github.com/religins/TAPBO/blob/master/2.JPG)

<h3>Kemudian pada bagian package silakan klik kanan dan pilih new Jframe</h3>
![3](https://github.com/religins/TAPBO/blob/master/3.jpg)
![3b](https://github.com/religins/TAPBO/blob/master/4.JPG)

<h3>Selanjutnya masuk pada bagian design dan isi Form Anda dengan ComboBox dan beberapa TextField, untuk contoh ini saya menggunakan 1 ComboBox dan 5 TextField</h3>
![4](https://github.com/religins/TAPBO/blob/master/5.jpg)
![4b](https://github.com/religins/TAPBO/blob/master/6.JPG)

<h3>Masuk ke bagian Source, isikan baris kode berikut</h3>
![5](https://github.com/religins/TAPBO/blob/master/7.JPG)

<h3>Perlu diketahui, karena kita menggunakan ComboBox sebagai yang memproses inputan, maka komponen terpenting dari baris kode tersebut adalah if (X.getItemSelected().equals(“)) yang berfungsi sebagaimana “jika item yang di select sesuai dengan “” di dalam kurung, maka...” kemudian aplikasi akan menjalankan baris kode di dalam if.
Selanjutnya untuk mengisi komponen data yang ingin ditampilkan, perlu adanya baris kode
TextField.setText(“”) untuk mengatur masing-masing TextField akan menampilkan output apa saja.
</h3>

<p>
Nama : Religi Nurhidayah Sakthi <br>
Kelas : XI RPL 1 <br>
Nomor : 29 <br>
Sekolah : SMK Telkom Malang
</p>
