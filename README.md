Clone this url in local folder. Then step following commnads to run project

1.  cd Larvel-CRUD		
2.  composer update

        copy .env.example file

        create one file called .env

        go to phpMyAdmin create one database called blog

            and changes following lines in .env files:
            DB_CONNECTION=mysql
            DB_HOST=127.0.0.1
            DB_PORT=3306
            DB_DATABASE=blog
            DB_USERNAME=root
            DB_PASSWORD=
3.  php artisan migrate
4.  php artisan key:generate
5.  php artisan serve
6.  open browser and type http://127.0.0.1:8000/products  in browser
