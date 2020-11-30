# kasirun
TUGAS PKK
PANDUAN APLIKASI POINT OF SALES
PERSIAPAN
1.	Memiliki CLI/Command Line Interface berupa Command Prompt (CMD) atau Power Shell atau Git Bash (selanjutnya kita sebut terminal).
2.	Memiliki Web Server (misal XAMPP) dengan PHP minimal versi 7.1.3.
3.	Composer telah ter-install, cek dengan perintah composer -V melalui terminal.
4.	Memiliki koneksi internet (untuk proses installasi).
I. INSTALASI
	1.	Silahkan ekstrak file kasirun.zip
	2.	Setelah itu, import terlebih dahulu database nya pada phpmyadmin, 	(sebenernya laravel menyediakan fungsi migrasi yangmana kita sebagai penerima 	source code tidak perlu mengimport database, hanya saja jika menggunakan cara 	tersebut data2 sample tidak akan ada)
	Nama file sql nya yaitu kasirun.sql
	3.	Jika sudah di import, jangan lupa pindahkan folder kasirun dimana saja 			terserah, setelah itu buka cmd lalu masuk ke direktori kasirun
4.	(Sesuai petunjuk installasi) Pada terminal, berikan perintah composer 	install. Ini yang perlu koneksi internet.
5.	Composer akan menginstall dependency paket dari source code 	tersebut hingga selesai.
6.	Jalankan perintah php artisan, untuk menguji apakah perintah artisan  	Laravel bekerja.
7.	Silahkan buka text editor ( Sublime text 3 or VS Code), lalu buka folder   	kasirun
8.	Duplikat file .env.example, lalu rename menjadi .env. ( jika sudah ada 	file .env tidak usah duplikat)
9.	Kembali ke terminal (cmd), php artisan key:generate.



10.	Setting koneksi database di file .env (DB_DATABASE, DB_USERNAME, DB_PASSWORD).
DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=kasirun
DB_USERNAME=root
DB_PASSWORD=
11.	Setelah selesai, Jalankan perintah php artisan serve maka dapat 	diakses dengan http://localhost:8000/
12.	Ouh iya, sebelum itu silahkan ketikkan npm install pada cmd, lalu 	kembali ke point 11







