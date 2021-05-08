Complete documentation for the this project it's not ready yet. If you want to test repository you must:

Clone the repo
https://github.com/Neerajamoli07/larawel_with_vue.git
Database
create database with name ecommerce_db
Create .env file and set
DB_DATABASE=crud_db
DB_USERNAME=root
leave password blank
Run by performing on the repo's folder to install all dependencies:
$ composer install
$ npm install
Now
$ php artisan migrate
Fill the database
$ php artisan db:seed
then run
$ php artisan serve in one terminal
$ npm run watch in second terminal
And access
http://127.0.0.1:8000