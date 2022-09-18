# newman-reporter-htmlextra
Automation Testing API RajaOngkir dengan newman-reporter-htmlextra

Langkah-langkah dalam melakukan automation testing API menggunakan newman-reporter-htmlextra:
1. Export terlebih dahulu API collection yang sudah ada test scriptnya
2. Export Environmentnya jika menggunakan global environment
3. Buka command prompt aka cmd
4. Masuk ke directory lokasi API collection dan environment yang sudah diexport sebelumnya
5. Ketik command newman run [API collection].json -e [Environment collection].json -n10 -r htmlextra  #**[-n] ini merupakan perintah untuk membuat iterasi**
6. Buka folder lokasi API collection dan environment disimpan, lalu buka folder newman
7. klik file .HTML nya #**API reporter menggunakan newman pun telah berhasil dibuat**
