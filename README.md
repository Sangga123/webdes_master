# webdes_master
Cara Install Project DENGAN github desktop
Untuk menginstal project ini anda harus memiliki Composer bagi yang belum install composer silahkan download Klik di sini tutorial cara instal composer klik di sini

Bagi yang sudah memiliki composer silahkan ikuti tutor dibawah ini

Klik tombol Clone or download
Klik Open in desktop
Klik open GithubDesktop.exe
Silahkan pilih lokasi path yang anda inginkan
Kemudian klik Clone
Tunggu sampai proses clone selesai
Buka folder porject yang sudah di clone melalui terminal
Lakukan composer install ketik
composer install
Tunggu sampai proses selesai
Buat database baru di phpmyadmin anda beri nama sesuka hati anda
Copy file .env.example yang ada di dalam folder project dan ubah namanya menjadi .env bagi yang menggunakan git bash atau terminal linux bisa ketik seperti dibawah
cp .env.example .env
bagi yang menggunakan terminal windows bisa ketik seperti dibawah

copy .env.example .env
Lakukan generate key ketik
php artisan key:generate
Buka file .env
Ubah konfigurasi database sesuai nama database yang anda buat tadi lalu simpan
lakukan migrate ketik :
php artisan migrate --seed
kemudian ketik :
php artisan storage:link
Finish project laravel bisa dijalankan dengan menggunakan development server dengan cara ketik
php artisan serve
Lalu ctrl+klik pada http://127.0.0.0:8000
Cara instal project TANPA github desktop
Bagi yang sudah memiliki composer silahkan ikuti tutor dibawah ini

Klik tombol Clone or download
Klik download zip
Silahkan pilih lokasi path yang anda inginkan
Kemudian klik Oke
Tunggu sampai proses download selesai
Extract here
Buka folder porject yang sudah di extract dengan terminal
Lakukan composer install ketik
composer install
Tunggu sampai proses selesai
Buat database baru di phpmyadmin anda beri nama sesuka hati anda
Copy file .env.example yang ada di dalam folder project dan ubah namanya menjadi .env bagi yang menggunakan git bash atau terminal linux bisa ketik seperti dibawah
cp .env.example .env
bagi yang menggunakan terminal windows bisa ketik seperti dibawah

copy .env.example .env
Lakukan generate key ketik
php artisan key:generate
Buka file .env
Ubah konfigurasi database sesuai nama database yang anda buat tadi lalu simpan
lakukan migrate ketik :
php artisan migrate --seed
kemudian ketik :
php artisan storage:link
Finish project laravel bisa dijalankan dengan menggunakan development server dengan cara ketik
php artisan serve
Lalu ctrl+klik pada http://127.0.0.0:8000
Login Admin http://127.0.0.0:8000/admin
email : admin@gmail.com
password : admin
