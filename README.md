# newman-reporter-htmlextra
Automation Testing API RajaOngkir menggunakan newman-reporter-htmlextra

Sebelum memulai automation testing menggunakan newman, hal yang perlu diperhatikan adalah "**Install dulu Node.js, Python, Newman dan reporter-htmlextra nya**"
1. Download node.js nya terlebih dahulu pada link berikut ini: https://nodejs.org/en/, disarankan pilih yang LTS yaaa!, kemudian Install
2. Tambahkan Node executable ke system path. Buka Control Panel > System and Security > System > Advanced System Settings > Environment variables. Tambahkan ke variabel PATH: C:\Program Files\nodejs **#Jika kamu menginstal Node di lokasi yang berbeda, kamu harus mengatur PATH yang sesuai dengan lokasi folder instalasinya.**

![image](https://user-images.githubusercontent.com/112541317/190885403-c14fdd6b-03f1-4638-8872-df52b6a293d5.png)



Langkah-langkah dalam melakukan automation testing API menggunakan Newman:
1. Export terlebih dahulu API collection yang sudah test scriptnya menggunakan Postman
2. Export Environmentnya jika menggunakan global environment
3. Buka command prompt aka cmd
4. Masuk ke directory lokasi API collection dan environment yang sudah diexport sebelumnya
5. Ketik perintah "newman run [API collection].json -e [Environment collection].json -n10"  **#[-n] ini merupakan perintah untuk membuat iterasi**
![image](https://user-images.githubusercontent.com/112541317/190885944-80ee467e-c7b4-4d97-ad46-aa382fce128d.png)
![image](https://user-images.githubusercontent.com/112541317/190885958-f101de21-eb79-455e-9389-fff573c2281c.png)
6. Lalu jika ingin membuat sebuah report automation API Testing dalam format html, bisa tambahkan perintah [-r htmlextra] 
example: "newman run [API collection].json -e [Environment collection].json -n10 -r htmlextra"
![image](https://user-images.githubusercontent.com/112541317/190886103-880d7ae5-4858-4e1b-8273-8c9536874a14.png)
7. Kemudian menuju folder lokasi API collection dan environment disimpan, lalu buka folder newman
8. Buka file .html nya #**API reporter menggunakan newman pun telah berhasil dibuat**
![image](https://user-images.githubusercontent.com/112541317/190885274-31f8ed89-a6ec-4143-9f4c-889f765de4a6.png)

