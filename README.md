# Memulai Kelas

Selamat datang di dokumentasi BWAStore. Terima kasih telah membeli kelas BWAStore dari BelajarKoding dan BuildWith Angga. Support kalian untuk kami para creator sangat kami apresiasi. Karena tanpa support dari kalian, kami tetap bisa untuk membuat konten tutorial yang terbaik untuk kalian 😄

Pastikan kalian membeli kelas ini langsung dari creatornya ya 😉. Kami sangat sedih jika kalian membeli dari pihak yang tidak bertanggung jawab. Jika kalian mendapatkannya selain dari BelajarKoding dan BuildWith Angga, kalian bisa lapor langsung ke kami ya!

Sebelum memulai belajar, ada beberapa informasi yang akan kami akan update secara berkala di halaman ini, dan kalian bisa cek berkala. Di halaman ini pula kami akan mendokumentasikan tutorial yang memang membutuhkan catatan seperti pemasangan tools dan deployment server

People with the spirit of learning, lets start! 😉

<hr>

# Source Code

Berkas Source Code pada video tutorial ini dapat kalian akses di GitHub **@belajarkoding** yang dapat kalian akses di
https://github.com/belajarkoding dengan nama repository store-\*.

Kalian dapat menggunakan dan memakai source code tersebut, dengan mengikuti lisensi MIT (selengkapnya baca bagian Lisensi dibawah). Source code ini **HANYA DAPAT DIGUNAKAN** untuk member kelas BWAStore dan tidak diizinkan untuk disebarkan kepada pihak selain member kelas BWAStore.

Jika anda mendapatkan konten video dan dokumentasi ini dari pihak selain BelajarKoding atau BuildWith Angga, dan bukan dari bagian member BWAStore, anda tidak diperkenankan untuk menggunakan source code ini.

<hr>

# Visual Studio Code

Sebelum kalian memulai membuat aplikasi, salah satu yang harus kalian siapkan adalah Code Editor. Disini saya merekomendasikan **Visual Studio Code** sebagai code editor. Selain gratis, kalian bisa memasang ekstensi yang membuat code editor kalian semakin powerful

Berkas instalasi bisa kalian unduh di https://code.visualstudio.com. Untuk cara install dapat langsung mengikuti aplikasi yang disediakan sesuai dengan sistem operasi yang digunakan

![VSCode](/images/vscode.png)

## Ekstensi

Untuk membuat pengalaman coding kalian lebih baik,saya rekomendasikan untuk memasang semua plugin dibawah ini.

### Ekstensi PHP & Laravel

1. Laravel Blade Snippets
2. Laravel Blade Spacer
3. Laravel Model Snippet
4. Laravel Snippets
5. Laravel Extra Intellisense
6. Laravel goto view
7. laravel-goto-controller
8. PHP Docblocker
9. PHP Intelephense
10. PHP Namespace Resolver
11. PHP Awesome Snippets
12. PHPDoc Generator
13. DotENV

### Ekstensi Lainnya

1. Auto Complete Tag
2. Auto Close Tag
3. Auto Rename Tag
4. Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets
5. Better Align
6. Bracket Pair Colorizer 2
7. Icon Fonts
8. Prettier
9. GitLens
10. Version Lens
11. Error Lens
12. Live SASS Compiler
13. Live Server
14. SonarLint
15. IntelliSense for CSS class names in HTML
16. Vetur

## Tema & Font

### Tema

1. Absolute Black
2. Monokai Pro

### Font

1. Operator Mono
2. JetBrains Mono

<hr>

# Menjalankan Live Server

Pada tutorial ini, saya menggunakan ekstensi Live Server dan Live SASS Compiler. Sebelum memulai slicing, pastikan kalian klik **GO Live** dan **Watch SASS** terlebih dahulu, dan pastikan bahwa file SASS kalian ter compile dengan cara mengecek file .css yang ada bersamaan dengan file .scss

![Live Server](./images/live-server.png)

Pastikan kalian selalu mengubah file .scss nya dan bukan .css nya, karena file .scss akan dicompile secara otomatis menjadi dan .css dan jika kalian menulis di file .css, maka perubahan kalian akan tertimpa.

<hr>

# Instalasi Tools Untuk Laravel

Sebelum kamu dapat melanjutkan tahap Laravel, kamu dapat memasang tools di bawah ini sesuai dengan sistem operasi yang kamu gunakan

## Windows

Untuk sistem operasi Windows, tools yang direkomendasikan untuk membuat aplikasi PHP dan Laravel adalah Laragon. Pada laragon, kamu juga dapat memasang aplikasi tanpa harus melakukan instalasi lewat command line

1. Masuk ke website laragon.org lalu klik Download ![Laragon 1](/images/laragon-1.png)
2. Pilih Laragon - Full ![Laragon 2](/images/laragon-2.png)
3. Ikuti instalasi yang ada dari installernya
4. Jalankan Laragon
5. Klik Start All ![Laragon 5](/images/laragon-5.png)
6. Klik “Menu” ![Laragon 6](/images/laragon-6.png)
7. Pilih Quick App -> Laravel ![Laragon 7](/images/laragon-7.png)
8. Masukkan nama project. Isi nama sesuai keinginan kalian ![Laragon 8](/images/laragon-8.png)
9. Proses instalasi laravel akan dijalankan oleh laragon. Untuk URL nya akan bisa diakses setelah proses instalasi selesai. ![Laragon 9](/images/laragon-9.png)
10. Untuk mengakses URLnya, kalian bisa membuka URL sesuai dengan nama project.
11. Jika kalian membuat nama projectnya bwastore, maka kalian akses http://bwastore.test ![Laragon 11](/images/laragon-11.png)
12. Kalian bisa langsung akses situs laravelnya. ![Laragon 12](/images/laragon-12.png)
13. Kalian pun bisa akses lewat aplikasi laragonnya.
14. Untuk membuka composer dan terminal, kalian bisa klik tombol Terminal yang ada di dalam aplikasi Laragon

## macOS

Untuk macOS, saya merekomendasikan untuk memakai Laravel Valet yang proses instalasinya dapat dibuka disini :
https://laravel.com/docs/6.x/valet

Jika tidak ingin menggunakan Laravel Valet, kalian bisa menggunakan MAMP untuk instalasi Tools nya yang dapat diunduh di
https://www.mamp.info/en/downloads/

Jika memakai MAMP, untuk composer nya harus dipasang terpisah dengan cara:
https://gist.github.com/kkirsche/5710272

## Linux

Untuk Linux, saya merekomendasikan untuk memakai Laravel Valet for Linux yang proses instalasinya dapat dibuka disini :
https://cpriego.github.io/valet-linux/

Jika tidak ingin menggunakan Laravel Valet, kalian bisa menggunakan XAMPP For Linux (LAMPP) untuk instalasi Tools nya yang dapat diunduh di
https://www.apachefriends.org/download.html

Sebagai alternatif, kamu bisa juga mengikuti tutorial di bawah ini jika ingin memasang secara manual:
https://www.linuxbabe.com/ubuntu/install-lemp-stack-nginx-mariadb-php7-2-ubuntu-18-04-lts

<hr>

# Adminer

Adminer adalah tools untuk mengatur database MySQL di server kita. Saya merekomendasikan menggunakan Adminer karena ringan dan mudah untuk digunakan

![Adminer](/images/adminer.png)

Untuk adminer, saya merekomendasikan untuk menggunakan versi dari @pematon di GitHub, yang bisa kalian akses di https://github.com/pematon/adminer-custom

Proses instalasinya, cukup kalian download zip / clone dan kalian taruh di folder www (jika menggunakan Laragon)

<hr>

# Deployment

1. Persiapan
   1. Buat Akun DigitalOcean
   2. Masukkan Paypal atau Kartu Kredit / Debit (Bisa pakai Jenius)
   3. Beli domain baru (kalau gak mau bisa pakai IP tapi tidak disarankan)
2. Buat Droplet Baru, Cari "LEMP" di Marketplace DigitalOcean
3. Login ke Server menggunakan SSH via Terminal / Command Line
   1. Untuk Windows https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse atau bisa pakai PuTTY
4. Ganti password root
5. Pasang composer `apt install composer`
6. Cek composer `composer -v`
7. Buka link ini sebagai referensi : https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-lemp-on-ubuntu-18-04
8. Pasang mbstring, xml dan bcmath (kebutuhan laravel dan composer)
   1. `sudo apt update`
   2. `sudo apt install php-mbstring php-xml php-bcmath zip php-cli unzip`
9. Buat database
   1. `sudo mysql`
   2. `CREATE DATABASE bwastore;`
   3. `GRANT ALL ON bwastore.* TO 'bwastore'@'localhost' IDENTIFIED BY 'passwordnya' WITH GRANT OPTION;` Petiknya jangan dicopas langsung tapi diketik ya
   4. `exit`
10. Masuk ke database baru
    1. `mysql -u bwastore -p`
    2. Masukin passwordnya
    3. `SHOW DATABASES;`
11. Setting laravel
    1. Masuk ke folder `cd /var/www`
    2. Pull project kalian dari github `git clone URL_GITHUB_KALIAN NAMA_DOMAIN_KALIAN`
    3. `ls` lalu `cd NAMA_DOMAIN_KALIAN`
    4. `composer install`
    5. `nano .env`
    6. Copas konfigurasi kalian dari local, ganti bagian database
    7. Ganti bagian `APP_DEBUG=false` dan `APP_ENV=production` biar kalau error ga muncul (mengamankan coding
    8. `php artisan storage:link`
12. Setting nginx

    1. `sudo chown -R www-data.www-data /var/www/NAMA_DOMAIN_KALIAN/storage`
    2. `sudo chown -R www-data.www-data /var/www/NAMA_DOMAIN_KALIAN/bootstrap/cache`
    3. `sudo nano /etc/nginx/sites-available/NAMA_DOMAIN_KALIAN`
    4. Copas ini :

    ```NAMA_DOMAIN_KALIAN
    server {
        listen 80;
        server_name NAMA_DOMAIN_KALIAN;
        root /var/www/NAMA_DOMAIN_KALIAN/public;

        add_header X-Frame-Options "SAMEORIGIN";
        add_header X-XSS-Protection "1; mode=block";
        add_header X-Content-Type-Options "nosniff";

        index index.html index.htm index.php;

        charset utf-8;

        location / {
            try_files $uri $uri/ /index.php?$query_string;
        }

        location = /favicon.ico { access_log off; log_not_found off; }
        location = /robots.txt  { access_log off; log_not_found off; }

        error_page 404 /index.php;

        location ~ \.php$ {
            fastcgi_pass unix:/var/run/php/php7.2-fpm.sock;
            fastcgi_index index.php;
            fastcgi_param SCRIPT_FILENAME $realpath_root$fastcgi_script_name;
            include fastcgi_params;
        }

        location ~ /\.(?!well-known).* {
            deny all;
        }
    }
    ```

    5. Ganti bagian server_name jadi `NAMA_DOMAIN_KALIAN`
    6. Ganti bagian root jadi `/var/www/NAMA_DOMAIN_KALIAN/public;`
    7. Save filenya
    8. `sudo ln -s /etc/nginx/sites-available/NAMA_DOMAIN_KALIAN/etc/nginx/sites-enabled/`
    9. `sudo nginx -t`
    10. Harus muncul kayak gini:

    ```
    nginx: the configuration file /etc/nginx/nginx.conf syntax is ok
    nginx: configuration file /etc/nginx/nginx.conf test is successful
    ```

    11. `sudo systemctl reload nginx`

13. Setting domain kalian
    1. Masuk ke panel hosting kalian (contoh disini pakai IDCloudHost)
    2. Masuk manage DNS
    3. Tambah Add Record
    4. Namenya isi `NAMA_DOMAIN_KALIAN.` Depannya pakai titik
    5. Type nya ganti A
    6. Isi selanjutnya (RDATA / IP Address) masukin nama IP digitalocean kalian (bisa dicek di dashboard DO nya)
    7. Add Record / Save
14. Buka website kalian sesuai `NAMA_DOMAIN_KALIAN`
15. Belum muncul? Sabar tunggu dulu mungkin belum propagasi. Tinggalin minum kopi dulu
16. Setting Database dan Migration
    1. `cd /var/www/NAMA_DOMAIN_KALIAN/`
    2. `php artisan migrate`
17. Install PHPMyAdmin (opsional)

    1. Referensi dari sini https://linuxize.com/post/how-to-install-phpmyadmin-with-nginx-on-ubuntu-18-04/
    2. `sudo apt install phpmyadmin`
    3. Skip dua pilihan, pilih OK (pakai TAB terus ENTER)
    4. Pilih yes
    5. Masukin password phpmyadmin
    6. `sudo mysql`
    7. `CREATE USER 'padmin'@'localhost' IDENTIFIED BY 'PASSWORD_SQL_PHPMYADMINYA';`
    8. `GRANT ALL PRIVILEGES ON *.* TO 'padmin'@'localhost' WITH GRANT OPTION;`
    9. `exit`
    10. `sudo nano /etc/nginx/snippets/phpmyadmin.conf`
    11. Copas ini :

    ```phpmyadmin.conf
    location /phpmyadmin {
        root /usr/share/;
        index index.php index.html index.htm;
        location ~ ^/phpmyadmin/(.+\.php)$ {
            try_files $uri =404;
            root /usr/share/;
            fastcgi_pass unix:/run/php/php7.2-fpm.sock;
            fastcgi_index index.php;
            fastcgi_param SCRIPT_FILENAME $document_root$fastcgi_script_name;
            include /etc/nginx/fastcgi_params;
        }

        location ~* ^/phpmyadmin/(.+\.(jpg|jpeg|gif|css|png|js|ico|html|xml|txt))$ {
            root /usr/share/;
        }
    }
    ```

    11. `nano /etc/nginx/sites-available/NAMADOMAINKALIAN`
    12. Masukkan `include snippets/phpmyadmin.conf;` didalam block `server{}`
    13. `sudo nginx -t`
    14. `sudo systemctl reload nginx`
    15. Masuk ke `http://NAMA_DOMAIN_KALIAN/phpmyadmin/`
    16. Kalau nemu error, jalanin ini : `sudo sed -i "s/|\s*\((count(\$analyzed_sql_results\['select_expr'\]\)/| (\1)/g" /usr/share/phpmyadmin/libraries/sql.lib.php` Petiknya jangan dicopas ketik manual

<hr>

# Lisensi dan Penggunaan

Source Code, Dokumentasi, dan Video Tutorial dilindungi oleh lisensi yang berbeda.

## Video Tutorial

Copyright © 2020 Galih Pratama & Angga Risky Setiawan (https://bit.ly/BWASTORE).

All rights reserved. Hak cipta dilindungi undang-undang.

[UU Nomor 28 Tahun 2014 tentang Hak Cipta](https://www.dgip.go.id/images/ki-images/pdf-files/hak_cipta/uu_pp/uu_hc_%2028_2014.pdf)

## Source Code & Dokumentasi

MIT License

Copyright (c) 2020 Galih Pratama

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<hr>

Source code ini HANYA DAPAT DIGUNAKAN untuk member kelas BWAStore dan tidak diizinkan untuk disebarkan kepada pihak selain member kelas BWAStore.

Jika anda mendapatkan konten video dan dokumentasi ini dari pihak selain BelajarKoding atau BuildWith Angga, dan bukan dari bagian member BWAStore, anda tidak diperkenankan untuk menggunakan source code ini.
