# Installation
Clone the repository-
Then cd into the folder with this command-
```sh
cd BLOGER
```
Then do a composer install
```sh
composer install /composer update
```
Then create a environment file using this command-
```sh
cp .env.example .env
```
Then edit .env file with appropriate credential for your database server. Just edit these two parameter(DB_USERNAME, DB_PASSWORD).

Then create a database named "anything could be " and then do a database migration using this command-
```sh
php artisan migrate  /php artisan migrate :fresh
```
```
generate application key, which will be used for password hashing, session and cookie encryption etc.
```sh
php artisan key:generate
```
Run ``` npm install ``` to install all front end dependencies
Run ``` php artisan storage:link ``` to link storage to public file

Run ``` php artisan serve ``` to run the project locally 

Run ``` php artisan --version ``` to check the project locally .

user can registration ,then login <<create any post or update or delete<< and can check the comment. 

one demo login data
email   :: easir956@gmail.com
password:: 018air,.








