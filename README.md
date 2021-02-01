## Laravel
### `installing Composer`
$ curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer

for kali linux  add this after the first command
$ mv composer.phar /usr/local/bin/composer

$ sudo laravel global require laravel/installer

Type on terminal:
 $ composer global require "laravel/installer"
 
When composer finish, type:
$ sudo nano ~/.bashrc

Paste and save:
$ export PATH="~/.config/composer/vendor/bin:$PATH"

Type on terminal:
$ source ~/.bashrc


to check if laravel is installed
Open another terminal window and type: laravel

$ laravel

$ composer



### `creating laravel project`
(windows)
After installing composer and xampp
1. create database
2. in the config > database.php file, set database_name, username as root, password(no password)
3. run php artisan migrate



