### Install php-fpm

`sudo apt install php-fpm`

### Find php service

`sudo systemctl list-units | grep php`

### Check php-fpm is running

`sudo systemctl status php7.4-fpm`

replace 7.4 with your php version
