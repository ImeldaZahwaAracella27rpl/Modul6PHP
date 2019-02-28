# Modul6PHP
1. Jelaskan menggunakan bahasa sendiri perbedaan antara cookies dan session!

JAWAB :

Cookies:
a. Cookies disimpan di sisi klien
b. Cookies tidak aman bagi klien karena cookies dapat disisipi program yang tidak diketahi klien.
Karena cookies tidak aman maka browser klien dapat di-set untuk menghapus cookies dan bahkan men-disable fungsi cookies. Menurut sumber lain cookies juga tidak aman bagi sisi server karena cookies dapat di-edit oleh klien.
c. Data yang disimpan ke dalam metode cookies dapat bertahan lebih lama dan dapat diatur waktu expired-nya.

Session
a. Disimpan disisi server
b. Lebih aman karena tidak ada file yang dimasukan ke sisi klien
c. Setelah web browser klien dimatikan maka data yang disimpan metode session akan hilang dan waktu expired juga tidak dapat diatur.

2. Bagaimana cara menghapus session dan cookies pada sebuah browser! 

JAWAB :

COOKIE :Penghapusan cookie dilakukan dengan cara mengirimkan nama cookie sama tetapi nilainya kosong

SESSION :Untuk menghapus data session, Anda bisa menggunakan konstruksi bahasa unset() atau fungsi session_destroy(). 

3. Berikan contoh kode dari pembuatan dan menghapus cookies dan session!
JAWAB :

COOKIE : 
=>Pembuatan nya dengan cara PHP menyediakan fungsi setcookie() yang digunakan untuk menetapkan nilai cookie. Adapun untuk mendapatkan nilai cookie, kita memanfaatkan variabel superglobal $_COOKIE. 
=>Menghapus dengan kode setcookie('nama_cookie', '', time() - 1 * 3600); 

SESSION :
=>Pembuatannya dengan cara PHP menyediakan fungsi session_start() yang harus selalu dipanggil sebelum kita dapat menetapkan maupun mengakses variabel session. Adapun untuk menetapkan nilai variabel session, kita menggunakan superglobal $_SESSION. 
=> Menghapusnya dengan kode unset() atau fungsi session_destroy().  



![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/1.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/2.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/3.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/4.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/5.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/6.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/7.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/8.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/9.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/10.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/11.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/12.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/13.PNG)
![alt text](https://github.com/ImeldaZahwaAracella27rpl/Modul6PHP/blob/master/Hasil/14.PNG)
