## Laravel Apple Produsts Blog
![index](https://raw.githubusercontent.com/TanishAfre/laravel-8-complete-blog-main/b12a0d89d512d664b8851a0eae99ff05541edb42/webPage.png?raw=true)

## Features in blog
• Comment on blog posts <br>
• Create and edit blog posts <br>
• Favorite blog posts <br>

## Favouraite Section Feature
![index](https://raw.githubusercontent.com/TanishAfre/laravel-8-complete-blog-main/master/Images/comment%20Section.png?raw=true)



•	Author: Code With Dary <br>
•	Twitter: [@codewithdary](https://twitter.com/codewithdary) <br>
•	Instagram: [@codewithdary](https://www.instagram.com/codewithdary/) <br>

## Requirements
•	PHP 7.3 or higher <br>
•	Node 12.13.0 or higher <br>

## Usage <br>
Setting up your development environment on your local machine: <br>
```
git clone git@github.com:codewithdary/laravel-8-complete-blog.git
cd laravel-8-complete-blog
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```

## Before starting <br>
Create a database <br>
```
mysql
create database laravelblog;
exit;
```

Setup your database credentials in the .env file <br>
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

Migrate the tables
```
php artisan migrate
```

## Contributing
Do not hesitate to contribute to the project by adapting or adding features ! Bug reports or pull requests are welcome.
