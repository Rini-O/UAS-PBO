# 📚 Laporan Pratikum Pemrograman Berorientasi Objek

Selamat datang di laporan pratikum **Pemrograman Berorientasi Objek**! 🎉😄

## 📖 Deskripsi
Laporan ini menjelaskan aplikasi Java berbasis GUI menggunakan Java Swing dan JPA (Java Persistence API) untuk menghubungkan data secara langsung dengan database dan menyederhanakan proses pengelolaan data Pada operasi CRUD (Create, Read, Update,Delete). Data Mahasiswa yang ditampilkan dalam tabel berisi informasi NIM, Nama, Alamat, Asal Sekolah, dan Nama Orang tua, yang kemudian disimpan kedalam database menggunakan pendekatan persistence. serta menyediakan button `upluod` yang dapat digunakan untuk mengimpor data dari file CSV.
selain itu untuk mencetak laporan Data Mahasiswa tersebut menggunakan Report dengan memanfaatkan library seperti JasperReports untuk menghasilkan laporan yang terformat dengan baik. untuk menghubungkan data mahasiswa tersebut, maka terdapat JframeLogin maupun Sign Up yang mencakup verifikasi data berdasarkan input username dan password, yang disimpan dan dikelola melalui database `UAS` pada table `datapengguna` menggunakan pendekatan persistence.

## 🔗 Langkah - langkah :

1. Membuat database baru `UAS` dan table baru `mahasiswa` & `datapengguna`

   ![image](https://github.com/user-attachments/assets/d5a9c57e-8df0-4274-b82f-54ca66d25c70)


   ![image](https://github.com/user-attachments/assets/871f2d0e-201e-4d58-b581-6308d001cf7d)



2. Koneksikan database

   ![image](https://github.com/user-attachments/assets/0a655117-7054-4aad-8941-75bf7c18a4e2)



3. Tambah JasperReports
- Menambahkan libraray
- Menambahkan report untuk membuat template laporan
- Memilih template laporan pada report
- Menentukan nama file (mahasiswa.jrxml) dan lokasi penyimpanan template laporan dalam proyek NetBeans (src/UAS)
- Menyisipkan Query SQL pada postgres untuk mengambil semua data dari tabel "mahasiswa" yang disimpan di database
-  menambahkan VM option untuk mengatasi akses server pada Java

  ![image](https://github.com/user-attachments/assets/76f8fa00-2de3-4cbd-a27e-5ef8f034762b)

  ![image](https://github.com/user-attachments/assets/8a335600-a891-4356-97c8-1f5865004ac9)



4. Tambah Persistence
   - Membuat kelas Entity Classes from Database
- Memilih JDBC
- Ketika berhasil maka akan muncul package baru yaitu META-INF
-Pada persistence.xml terdapat Include Entity classes
-Maka pada package MataKuliah terdapat entity classes Mahasiswa_1 & Datapengguna

  ![image](https://github.com/user-attachments/assets/248fcc4a-a8b6-4749-b50a-d0cae4ffdf49)


5. Membuat Jframe Mahasiswa 
![image](https://github.com/user-attachments/assets/ff4e9308-bef8-4e9c-a9dd-f5b2004ec96f)

-Memasukkan source code insert
![image](https://github.com/user-attachments/assets/0fe4e241-85c8-4621-a69a-bb4b8ec75a41)


-Memasukkan source code delete
![image](https://github.com/user-attachments/assets/dad3f5a5-a9c8-4686-96fd-cff5c92ec760)


-Memasukkan source code Update 
![image](https://github.com/user-attachments/assets/10b4ed73-08d4-4557-aadd-2ea03ca56865)



-Memasukkan source code Upluod agar dapat mengimpor data csv
![image](https://github.com/user-attachments/assets/258a8535-3db9-4ccb-9d11-0230739152d1)



-Memasukkan source code Cetak untuk mencetak laporan data mahasiswa menggunakan jasper report 
![image](https://github.com/user-attachments/assets/19eea83c-3a59-49d8-9635-b759c7809f79)



-Membuat metodh ShowTable agar dapat tampil di tabel Jframe mahasiswa
![image](https://github.com/user-attachments/assets/6ed477dc-b030-41f8-b20b-c22601c5f2b4)



-Memasukkan source code pada tabel mahasiswa agar dapat di klik dan dapat tampil di form mahasiswa
![image](https://github.com/user-attachments/assets/9ef09716-0093-46fa-a036-d790a476d6f5)


6. Membuat Jframe Sign Up


   ![image](https://github.com/user-attachments/assets/59e969a4-1c68-4b55-a901-9d4e0abe9b02)

-Membuat metodh cek karakter password agar pasword yang dibuat sesuai 
![image](https://github.com/user-attachments/assets/7e933c6d-f14a-40d3-ac48-54452b090ba3)

-Memasukan source code pada button Sign UP
![image](https://github.com/user-attachments/assets/0c91ec7e-43d4-407f-b87f-9fd0860aed26)

![image](https://github.com/user-attachments/assets/477d84d0-1ec3-426b-9437-a78d8d24747f)


7. Membuat Jframe Login




   ![image](https://github.com/user-attachments/assets/aaaad208-c344-4b3b-b1c3-d9d45d4ae717)


-Memasukkan Source code show untuk menampil password yang dimasukkan
![image](https://github.com/user-attachments/assets/f337369a-3174-485b-9445-88c854855958)

-Memasukkan source code pada label Sign Up agar langsung terhbung pada frame Sign UP
![image](https://github.com/user-attachments/assets/cc97676f-7859-43cc-bc75-7abdf284b787)


-Memasukkan source code Login kemudian terhubung ke form Mahasiswa
![image](https://github.com/user-attachments/assets/5e2bc945-3224-4151-b516-baa4b52d29c7)






   














   

   



