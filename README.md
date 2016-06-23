# Shopify-Private-Apps
Shopify Private App project using phpish/shopify

1- Install Composer In Your Project
(i)Run this in your command line:
   curl -sS https://getcomposer.org/installer | php
   Or download composer.phar into your project root.
(ii)Install Dependencies
    Execute this in your project root.

(iii)php composer.phar install
    Autoload Dependencies
    If your packages specify autoloading information, you can autoload all the dependencies by adding this to your code:
    require 'vendor/autoload.php';
    for mor info please visit:- https://packagist.org/
2-Create a private app.
3-Update conf.php with the private app's credentials.
4-Check out the .php files and see how they work. (e.g., http://path-to-new_prj/get_shop.php)
