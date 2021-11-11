## Laravel 8 Blog



## Requirements
•	PHP 7.3 or higher <br>
•	Node 12.13.0 or higher <br>

## Uso<br>
Ambiente  <br>


cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```


Criar Bamco de dados <br>
```
mysql
create database laravelblog;
exit;
```

Configiguração do arquivo .env file <br>
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

Migrar tabelas
```
php artisan migrate
```

