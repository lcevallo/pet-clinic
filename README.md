
# CURSO DE PET CLINIC FILAMENTPHP

Para crear un modelo y la migración
php artisan make:model Appointment -m



composer create-project laravel/laravel filamentphp

composer require filament/filament:"^3.2" -W

php artisan filament:install --panels

php artisan make:filament-user

copiar el contenido del archivo .env.example
composer install como el npm install
Crear la base de datos
php artisan key:generate
php artisan migrate


git init
git add .
git commit -m "Empezamos con pet clinic"
git branch -M main
git remote add origin https://github.com/lcevallo/pet-clinic.git
git push -u origin main
