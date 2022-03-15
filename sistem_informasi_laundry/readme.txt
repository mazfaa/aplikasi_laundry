Cara Install Source Code Sistem Infomasi Manajemen Laundry Gratis
1. Pastikan kamu sudah menginstall tools yg diperlukan untuk menggunakan laravel, karena project ini di bangun dengan Framework Laravel.
2. Silahkan Clone dengan perintah 'Git Clone https://github.com/andes2912/laundry.git'.
3. Jalankan perintah 'Composer Install' pada direktori project
4. File .env sudah include, kalian hanya perlu menyesuaikan nama database
5. Buat DB dan jalankan perintah 'php artisan migrate'
6. Kemudian jalan perintah 'php artisan db:seed --class=AdminSeeder', ini untuk mengenerate Akun
7. Login dengan 
user='admin@laundry.com' 
password='123456'