# newman-reporter-htmlextra
Automation Testing API RajaOngkir menggunakan newman-reporter-htmlextra

Sebelum memulai automation testing menggunakan newman, hal yang perlu diperhatikan adalah "**Install dulu Node.js, Python, Newman dan reporter-htmlextra nya**"

Langkah-langkah dalam melakukan automation testing API menggunakan Newman:
1. Export terlebih dahulu API collection yang sudah diberikan test scriptnya menggunakan Postman serta export juga Environmentnya jika menggunakan global environment
2. Buka command prompt aka cmd
3. Masuk ke directory lokasi disimpannya API collection dan Environment yang sudah diexport sebelumnya
4. Ketik perintah "newman run [API collection].json -e [Environment collection].json -n10"  **#[-n] ini digunakan untuk membuat iterasi (loop/perulangan)**
![image](https://user-images.githubusercontent.com/112541317/190885944-80ee467e-c7b4-4d97-ad46-aa382fce128d.png)
![image](https://user-images.githubusercontent.com/112541317/190885958-f101de21-eb79-455e-9389-fff573c2281c.png)
5. Lalu jika ingin membuat sebuah report automation API Testing dalam format html, bisa tambahkan perintah [-r htmlextra] pada akhir command
**example:** "newman run [API collection].json -e [Environment collection].json -n10 -r htmlextra"
![image](https://user-images.githubusercontent.com/112541317/190886103-880d7ae5-4858-4e1b-8273-8c9536874a14.png)
6. Kemudian buka folder disimpannya file json API collection dan Environment, lalu buka folder newman
7. Buka file .html #**API reporter menggunakan newman pun telah berhasil dibuat**
![image](https://user-images.githubusercontent.com/112541317/190885274-31f8ed89-a6ec-4143-9f4c-889f765de4a6.png)
