# CMD_MYSQL
1. Ini adalah kumpulan perintah MYSQL menggunakan CMD
KETIK CMD pada Windows R

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/c2066cd6-fda6-4cd6-ae2b-b3fbffd3d0d7)

2. Untuk menjalankan XAMPP seperti berikut -> cd xampp -> xampp-control.exe
   
![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/d16a0a72-794f-4a60-bd1f-dd023ba8b4a8)

3. Maka jendela XAMPP Control Panel akan jalan, kemudian jalankan Apache dan Mysql 

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/5d9de471-32ac-4799-a1ce-f9106c898c35)

4. Masuk ke folder -> mysql/bin/ atau /xampp/mysql/bin/

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/01cd67c2-eb1e-471a-9180-1a8bc590753b)

5. Masuk ke mysql dengan perintah berikut jika masih default tanpa pasword -> mysql -uroot

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/be04cb4b-b30a-4d61-91bf-a052d47f2309)

6. Maka akan masuk ke tampilan mysql

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/4e52592e-630f-45ef-96c8-cf260c4b6a5f)

7. Membuat databases latihan2 dengan -> create database latihan2;
   
![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/19e48d2e-3513-4d11-818d-88b01ce78db6)

8. Gunakan database latihan2 -> use latihan2;
   
![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/e95f8768-46be-401e-bcf5-fd211238ca0d)

9. Membuat TABEL -> create table data ( id int, nik varchar(18), nama varchar(255), alamat varchar(255), kota varchar(255), pendidikan varchar (255)) 

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/281f21d7-a576-4a55-a98b-97e4f4465230)

10. cek dengan -> desc data;

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/aec5ebfd-78b5-48f0-93ef-285b60ba62c2)

11. memasukan data ->  insert into data values ('1', '3329081608930010', 'Farchan Muzaki', 'Jl. Demang Sapingi RT.04 RW.02 Dumeling', 'Brebes', 'S-1 Teknik Informatka');

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/b8551c19-4678-4969-8002-a053711e5e60)

13. cek filed pada tabel data -> select*from data;

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/0c778895-68da-4271-912b-81500c7b4063)

14. untuk menambahkan data pada tabel lebih dari 1 field dengan -> insert into data values ('2', '3329081209930010', 'Abu Umar S.', 'Jl. Cendrawasih RT.10 RW.05 Cipetir', 'Tangerang Selatan', 'S-1 Teknik Kimia'), ('3', '3329081201960008', 'Sabila Rosyidah', 'Jl, Raya Banjaratma RT.03 RW.09 Banjaratma', 'Brebes', 'S-1 Farmasi');
  
![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/983168bb-a4c2-4256-bcab-b23e19e7e45c)

15. Hasilnya

![image](https://github.com/farchanmuzaki/CMD_MYSQL/assets/116914974/099d2617-3d8b-4152-bd60-ec545b5c9bc9)





   
