# Final-Project-Intro-to-Software-Engineering

--> #Latar Belakang:
Andi adalah seorang pemilik supermarket besar di salah satu kota di Indonesia dan Andi memiliki sebuah rencana untuk melakukan perbaikin pada proses bisnis supermarket yang dimilikinya, yakni Andi akan membuat sebuat sistem kasir berbasiskan CRUD (Create, Read, Update, dan Delete) Terminal yang sifatnya bisa self-service di supermarket miliknya dengan harapannya:

1. Customer bisa langsung memasukkan item yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli serta fitur lainnya.
2. Customer yang tidak dalam satu kota tersebut bisa melakukan pembelian barang dari bisnis supermarket yang dimiliki oleh Andi



--> # Requirements atau Objectives yang dibutuhkan untuk membuat program:
Dari Brief Technical Documentation yang telah diberikan oleh tim Pacmann Ai, saya bisa langsung mengetauhi dan memutuskan bahwasannya program kasir supermarket yang dimiliki oleh Andi haruslah dibuat berbasiskan CRUD Terminal. Dimana nantinya user bisa melakukan penambahan barang, pengubahan barang/pengeditan barang, serta menghapus barang belanjaannya. Oleh karenanya sistem yang akan dijabarkan/didevelopment/dibuat mengandung kriteria sebagai berikut:

1. Membutuhkan database
2. Membutuhkan pemrograman functional programming dan oop programming agar bisa terhubung dengan database.




--> # Penjelasan Alur Code:

1. Pertama-tama membuat koneksi database agar barang belanjaan milik si user tersimpan dengan rapi pada database.
2. Lalu yang kedua membuat kode program berbasiskan functional programming atau oop programming dengan terquery dan terhubung dengan database. Adapun kode program yang dibuat adalah sederhana saja berbasiskan CRUD (Create, Read, Update, dan Delete)



--> # Penjelasan Mengenai Functions untuk apa:

1. Melakukan import sqlite 3 terlebih dahulu untuk bisa terkoneksi dengan database
2. Membuat database dengan menggunakan sqlite3 dengan mengetikkan perintah crate table kasir_transaction dengan nama database-nya transaction.db
3. Barulah langkah ketiga membuat function Create, yang mana didalam function ini berisikan untuk membuat isi daripada database-nya.
4. Lalu selanjutnya dilanjutkan dengan membuat function Read, dimana didalam function ini nantinya digunakan oleh user untuk menampilkan barang belanjaannya.
5. Berikutnya dilanjutkan dengan membuat function Update, function ini digunakan untuk user bilamana ingin melakukan perubahan data terhadap barang belanjaannya.
6. Yang terakhir adalah membuat function Delete, function ini digunakan untuk user menghapus barang belanjaan yang tidak jadi dibeli, menghapus barang belanjaan yang salah di-input-kan, serta menghapus barang belanjaan tertentu saja (tidak semuanya).

Tak lupa pada masing-masing 'Function' terhubung dan terindeks dengan database, supaya data proses belanja milik si user tersimpan dengan baik.




--> # Demontrasi Code dengan Test Case:
Jujur saja ketika saya melakukan running pada code program yang telah saya buat semuanya berjalan sangat lancar tanpa adanya error, bug, ataupun kesalahan penulisan identasi. Namun pada saat saya lakukan "unit-test" di dalam google collaboratory terdapat kemunculan pesan error module not found. Error tersebut sudah saya lakukan pencarian pada stack overflow, kotak kode, ataupun website yang sejenis namun tetap saja tak membuahkan hasil, sehingga bisa dibilang "unit test tidak berjalan dengan lancar.

--> # Conclusion:
Diharapkan kode program kasir supermarket berbasikan CRUD Terminal bisa memberikan akses kemudahan terhadap Andi serta bisa memberikan sisi rasa kepuasan, kebahagiaan, dan kenyamanan dari pengunjung ataupun pembeli dari supermarket milik Andi. Dari Tugas Project Akhir Intro to Software Engineering inilah saya juga telah mempelajari bahwasannya konsep fitur CRUD adalah sebuah konsep "Functional Programming" ataupun "OOP Programming" yang bisa dipakai atau diterapkan pada saat akan membuat aplikasi-aplikasi berskala kecil-besar, karena fitur CRUD adalah sebuah fitur bassic yang harus dimiliki oleh tiap-tiap sistem.

Best Regards,
Mochammad Nafisa Chafith
