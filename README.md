**#latihan 1**

**Perintah dasar git**

1. ***git init***,perintah untuk membuat repositary local

2. ***git add***,perintah untuk menambahkan file baru , atau perubahan pada file pada staging sebelum proses commit

3. ***git commit***,perintah untuk menyimpan perubahan kedalam database git 

4. ***git push -u origin master***,perintah untuk mengirim perubahan pada repository local menuju server repository

5. ***git clone [url]*** ,perintah untuk menambahkan remote server/repository server pada local repository

**Langkah-langkah menggunakan git**

✓langkah pertama kalian buat folder di komputer kalian di bagian ***D:\pemrograman*** dan direktori aktif menjadi ***D:\pemrograman\latihan1***

✓langkah berikutnya buka folder yang kalian buat tadi klik kanan buka dengan git bash

✓sebelum berlanjut ke langkah berikutnya kalian bisa membuat reposirory dulu di github, nama file latihan1

✓ Selesai masuk ke git bash kalian masukan file  ***git config --global user.name "email github kalian"
dan git config --global user.name "kata sandi kalian"***

✓selanjutnya kalian ketikan seperti gambar dibawah ini untuk membuat repository local

<img src="latihan1 langkah pertama.png" alt="latihan1 langkah pertama.png"/>

✓langkah selanjutnya kalian ketik  ***git init***

<img src="latihan1 langkah kedua.png" alt="latihan1 langkah kedua.png"/>

✓ketikan seperti gambar di bawah ini

<img src="latihan1 langkah ketiga dan keempat.png" alt="latihan1 langkah ketiga dan keempat.png"/>

✓langkah berikutnya kalian ketik  ***git add README.md***

<img src="latihan1 langkah kelima.png" alt="latihan1 langkah kelima.png"/>

✓Setelah itu kalian ketikan ***git status***

<img src="latihan1 langkah keenam.png" alt="latihan1 langkah keenam.png"/>

✓Selanjutnya ketik ***git commit -m "file pertama saya"***

<img src="latihan1 langkah ketujuh.png" alt="latihan1 langkah ketujuh"/>

✓berikutnya ketik ***git remote add origin*** dan kalian masukan ***link repository github*** yang sudah kalian buat , contohnya seperti dibawah ini

<img src="latihan1 langkah kedelapan.png" alt="latihan1 langkah kedelapan.png"/>

✓setelah itu ketik ***git push -u origin master*** hasilnya seperti gambar ini

<img src="latihan1 langkah kesembilan.png" alt="latihan1 langkah kesembilan.png"/>

✓nah disini kalian membuat isi readme.md dengan cara ketik
***nano*** nanti akan muncul gambar seperti ini misalnya kalian membuat tutorial cara menggunakan git

<img src="latihan1 langkah ke10.png" alt="latihan1 langkah ke10.png"/>

<img src="latihan1 langkah ke13.png" alt="latihan1 langkah ke13.png"/>

✓Selanjutnya jika kalian sudah membuat isi readme.nya kalian simpan dengan menenkan tombol ***ctrl+x*** lalu tekan ***Y*** setelah itu tekan ***enter***

✓hasilnya file akan secara otomatis terkirim atau terhubung ke Akun Github kalian ,Coba kalian cek repository yang kalian buat tadi apakah berubah readme.nya kalau berubah dan ada file tutorial yang kalian buat artinya berhasil.
