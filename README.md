Clone this url in local folder. Then step following commnads to run project

cd Larvel-CRUD		

composer update

    copy .env.example file

    create one file calles .env

    go to phpMyAdmin create one database called blog

        and changes following lines in .env files:
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=blog
        DB_USERNAME=root
        DB_PASSWORD=
php artisan migrate

php artisan serve
