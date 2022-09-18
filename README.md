# newman-reporter-htmlextra
Automation Testing API RajaOngkir menggunakan newman-reporter-htmlextra

Sebelum memulai automation testing menggunakan newman, hal yang perlu diperhatikan adalah "**Install dulu Node.js, Python, Newman dan reporter-htmlextra nya**"
1. Download node.js nya terlebih dahulu pada link berikut ini: https://nodejs.org/en/, disarankan pilih yang LTS yaaa!
2. Tambahkan Node executable ke system path. Buka Control Panel > System and Security > System > Advanced System Settings > Environment variables. Tambahkan ini ke variabel PATH: C:\Program Files\nodejs **#Jika kamu menginstal Node di lokasi yang berbeda, kamu harus mengatur PATH yang sesuai dengan lokasi folder instalasinya.**

![image](https://user-images.githubusercontent.com/112541317/190885403-c14fdd6b-03f1-4638-8872-df52b6a293d5.png)



Langkah-langkah dalam melakukan automation testing API menggunakan newman-reporter-htmlextra:
1. Export terlebih dahulu API collection yang sudah ada test scriptnya
2. Export Environmentnya jika menggunakan global environment
3. Buka command prompt aka cmd
4. Masuk ke directory lokasi API collection dan environment yang sudah diexport sebelumnya
5. Ketik perintah "newman run [API collection].json -e [Environment collection].json -n10 -r htmlextra"  **#[-n] ini merupakan perintah untuk membuat iterasi**
![image](https://user-images.githubusercontent.com/112541317/190885338-0be4eb6a-c7c5-48a8-9a4e-2054503b6512.png)
6. Buka folder lokasi API collection dan environment disimpan, lalu buka folder newman
7. klik file .HTML nya #**API reporter menggunakan newman pun telah berhasil dibuat**
![image](https://user-images.githubusercontent.com/112541317/190885274-31f8ed89-a6ec-4143-9f4c-889f765de4a6.png)

