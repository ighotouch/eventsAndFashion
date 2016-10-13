# Events And Fashhion

## Use the following command to get you started
composer update
php artisan vendor:publish
php artisan migrate
php artisan aimeos:setup --option=setup/default/demo:1
php artisan aimeos:cache
php artisan cache:clear

##To add admin account
php artisan aimeos:account --admin <email>

if you get Mshop Exception try the command below
php artisan aimeos:setup --option=setup/default/demo:1 1>setup.log 2>setup.err


## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
