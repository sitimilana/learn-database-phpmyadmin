**Perhatikan skema/model relasional/EER diagram dari database berikut.**
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/343ec541-80ed-4256-8d0f-3422f27b6e76)

**Skema tersebut adalah sekema database pada sebuah sistem informasi penjadwalan di Jurusan
Teknologi Informasi. Pertama-tama, buatlah database tersebut dengan mengeksekusi barisbaris
kode DDL berikut dan jelaskan maksud dari setiap tahapan tersebut.**

1. Pertama yaitu membuat database baru 
![Screenshot 2024-05-16 085957](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/cea63ff5-62b9-4f88-b935-a9940ce7b8e5)

2. Selanjutnya show databases lalu use database yang dibuat
   
![Screenshot 2024-05-16 090144](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/728153c9-2865-4f4b-aa10-00e943a56d87)

3. Membuat table dosen
   
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/dec720d2-0b25-4f9c-ad4f-c94d823f01f9)

4. Membuat table hari
   
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/44bffdb8-6a90-4c94-affd-7919692c65d3)

5. Membuat table jadwal
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/225c4e54-5efc-4fd3-843d-2793212dbf4e)

6. Membuat table jp

![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/2259c6a2-fafb-4b9c-9ec6-a3b68455f1fd)

7. Membuat table kelas
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/66a69674-5321-44ae-9afa-599effa61cbd)

8. Membuat table mk
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/f35dab94-e7a1-4b32-ba2c-6a2f8dd32c5b)

9. Membuat table prodi
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/fb72a887-85ac-4f46-809b-e6f59237ef90)

10. Membuat table ruang
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/b748749d-12bb-4788-b8f8-784d06e864aa)

11. Menambahkan kunci utama (PRIMARY KEY) pada tabel yang sudah ada, dalam tabel dosen, hari, jadwal, jp, kelas, mk, prodi, ruang.
    
![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/4f8e1e0f-f40e-465f-bf6f-4c07e592b08e)

12.  Mengubah definisi kolom kode_jadwal pada tabel jadwal menjadi bilangan bulat hingga 10 digit, tidak boleh bernilai NULL, dan nilai kolom ini akan otomatis bertambah setiap kali baris baru ditambahkan ke tabel.

![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/2cbc73ae-3957-4dbb-812e-41788384d4dc)

13.  Selanjutnya menambahkan kunci asing (FOREIGN KEY) pada kolom-kolom tersebut di tabel jadwal yang merujuk ke kolom dengan nama yang sama di tabel-tabel yang sesuai. Ini akan memastikan integritas data antara tabel jadwal dan tabel-tabel lainnya.

![image](https://github.com/sitimilana/learn-database-phpmyadmin/assets/160199567/d59dab2a-e6ab-4532-a307-4140d819f0ba)



