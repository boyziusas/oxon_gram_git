# oxon_gram_git

Telegram Web client integration for Oxon Technologies company using Madelineproto Telegram library for Laravel framework

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/8.x/installation/)

//
PHP == 7.4.1


Clone the project repository by running the command below if you use SSH

```
git clone git@github.com:boyziusas/oxon_gram_git.git
```

If you use https, use this instead

```
git clone https://github.com/boyziusas/oxon_gram_git.git
```

Switch to the repo folder

```
cd oxon_gram_git
```

Install all the dependencies using composer

```
composer install
```

Copy the example env file and **change api_id and api_hash entries from core.telegram.com page** in the .env file**

```
cp .env.example .env
```
**change api_id and api_hash entries from core.telegram.com page** in the .env file** & Generate a new application key

```
php artisan key:generate
```

Start the local development server

```
php artisan serve
```

You can now access the server at http://127.0.0.1:8000

**Used command list**

```
git clone git@github.com:boyziusas/oxon_gram_git.git
cd oxon_gram_git
composer install
cp .env.example .env
php artisan key:generate
php artisan serve 
```
