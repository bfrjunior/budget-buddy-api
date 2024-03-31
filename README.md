# Budget-buddy-api

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins de desenvolvimento e teste.


### 🔧 Instalação

Clone o Repositorio:
```
git clone https://github.com/seu-usuario/budget-buddy-api.git
```
Install dependencies:
```
composer install
```
Copy the .env.example file to .env and configure your environment variables:
```
cp .env.example .env
```
Run the database migrations and seeders to set up the database:
```
php artisan migrate --seed
```
To start the development server, run the following command:
```
php artisan serve
```
You can now access the API at http://localhost:8000

## 🛠️ Construído com

* [Laravel](https://laravel.com/)
* [Php 8](https://www.php.net/)
* [Mysql]()

