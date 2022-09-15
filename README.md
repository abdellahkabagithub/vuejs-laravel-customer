php artisan make:model Customer -mf
php artisan make:Controller Api\CustomerController --api --resource -model=Customer
php artisan make:resource CustomerResource
php artisan route:list --name=customer
#Authentification
composer require laravel/breeze
php artisan breeze:install
php artisan migrate:fresh --seed
#Installation de vue js 3
npm i --save-dev @vitejs/plugin-vue vue
#Information
Une api ressource