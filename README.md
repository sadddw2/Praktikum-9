Smart Quiz Generator - Testing
Deskripsi

Repository ini berisi implementasi Unit Testing dan Feature Testing pada aplikasi Smart Quiz Generator menggunakan PHPUnit Laravel.

Test Case
User Access Test
Kuis Test
User CRUD Test
Role Access Test
Menjalankan Testing

Menjalankan seluruh test:

php artisan test

Menjalankan test tertentu:

php artisan test tests/Feature/UserAccessTest.php
php artisan test tests/Feature/KuisTest.php
php artisan test tests/Feature/UserCrudTest.php
php artisan test tests/Feature/RoleAccessTest.php
Hasil Pengujian
Test	Status
User Access Test	PASS
Kuis Test	PASS
User CRUD Test	PASS
Role Access Test	PASS
Coverage

Modul yang diuji:

Authentication
User Access
User CRUD
Kuis
Role Access
Author

Ardhafillah
Application Project III
