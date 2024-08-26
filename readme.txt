Laravel 10 (Backend):
PHP >= 8.3
Composer
Laragon dengan php versi 
Langkah Langkah:
setting fike .env
php artisan key:generate
php artisan migrate
php artisan serve --host 192.168.100.5 --port 80 
(host nya sesuaikan dengan ip laptop/computer, buat windows cek nya pake ipconfig)

test login ke website (tidak bisa register jadi harus masuk pake akun yang sudah di generate di database->seeders->databaseseeder.php
login pakai email dan password itu



Flutter (Frontend):
Flutter SDK
Dart SDK
Android Studio

Langkah Langkah:
flutter pub get

setting ip back-end : lib->core->constants->variables.dart Ganti base url nya
flutter run
