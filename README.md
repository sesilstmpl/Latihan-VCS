# Latihan-VCS
## Belajar GIT

### Apa Itu GIT?
Git adalah Version Control System yang digunakan oleh para developer untuk mengembangkan software secara bersama-sama
Berikut adalah tutorial menggunakan Git 
1. Buka github.com lalu create new repository dengan nama "Latihan VCS" dengan settingan publik dan add README file
![Gambar 1](Gambar/ss1.png)
2. Setelah itu copy link repositorynya
![Gambar 2](Gambar/ss2.png)
3. Lalu buka Git Bash
4. Karena kita ingin membuat repositorynya pada date C, maka ketik cd /c/ lalu git clone dan paste link repositorynya, maka akan muncul seperti ini
![Gambar 3](Gambar/ss3.png)
5. Lalu buka file pada data C, dan repositorynya sudah ada di data C
![Gambar 4](Gambar/ss4.png)
6. Lalu buka file readme tersebut, dan isi sesuai keinginan. Misalnya seperti ini
![Gambar 5](Gambar/ss5.png)
7. Setelah itu kembali lagi ke git, ketik git status untuk melihat statusb git pada saat itu. Karena kita telah merubah isi readme nya, maka kita ketik git add 'README.md' lalu ketik git commit -m 'Perubahan Pada Readme' dan ketik git push -u origin main untuk menambahkan pembaruan readme tersebut dalam repository github.
![Gambar 6](Gambar/ss6.png)
8. Maka pada github akan muncul seperti ini :
![Gambar 7](Gambar/ss7.png)
9. Jika ingin menampilkan Gambar pada repository, maka terlebih dahulu buat folder baru lalu isi gambarnya dalam folder tersebut. lalu kembali ke github ketik git add 'Gambar' lalu ketik git commit -m 'Menambah folder gambar' dan ketik git push -u origin main untuk menambahkan folder tersebut ke dalam repository.
![Gambar 8](Gambar/ss8.png)
10. Lalu lanjut pada readme, ketik ![Gambar 1](lokasi gambar/nama gambar )
![Gambar 9](Gambar/ss5.png)
11. Pada github akan muncul seperti ini 
![Gambar 10](Gambar/ss9.png)
12. -SELESAI-