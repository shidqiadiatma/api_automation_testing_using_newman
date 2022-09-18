# newman-reporter-htmlextra
Automation Testing API RajaOngkir menggunakan newman-reporter-htmlextra

Sebelum memulai automation testing menggunakan newman, hal yang perlu diperhatikan adalah "**Install dulu Node.js, Python, Newman dan reporter-htmlextra nya**"
1. Download node.js nya terlebih dahulu pada link berikut ini: https://nodejs.org/en/, disarankan pilih yang LTS yaaa!
2. Tambahkan Node executable ke system path. Buka Control Panel > System and Security > System > Advanced System Settings > Environment variables. Tambahkan ini ke variabel PATH: C:\Program Files\nodejs **#Jika kamu menginstal Node di lokasi yang berbeda, kamu harus mengatur PATH yang sesuai dengan lokasi folder instalasinya.**


Langkah-langkah dalam melakukan automation testing API menggunakan newman-reporter-htmlextra:
1. Export terlebih dahulu API collection yang sudah ada test scriptnya
2. Export Environmentnya jika menggunakan global environment
3. Buka command prompt aka cmd
4. Masuk ke directory lokasi API collection dan environment yang sudah diexport sebelumnya
5. Ketik perintah "newman run [API collection].json -e [Environment collection].json -n10 -r htmlextra"  #**[-n] ini merupakan perintah untuk membuat iterasi**
6. Buka folder lokasi API collection dan environment disimpan, lalu buka folder newman
7. klik file .HTML nya #**API reporter menggunakan newman pun telah berhasil dibuat**
