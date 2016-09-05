PHP Selenium
=====

A simple project integrated PHPUNIT,Facebook webdriverd


System Requirements
===================

XHGui has the following requirements:

 * PHP version 5.6 or later.
 * [Composer](https://getcomposer.org/)
 * [Selenium Standalone Server](http://www.seleniumhq.org/download/)
 * [Firefox driver](https://github.com/mozilla/geckodriver/releases)
 * [PHPUNIT](https://phpunit.de)



Getting Started
============
Download or Clone the project
```sh
git clone https://github.com/shushanxingzhe/php-selenium.git
```

Update the dependency
```sh
cd /path/to/project
composer update
```

Run Selenium Server with Firefox driver
```sh
java  -Dwebdriver.gecko.driver=/path/to/firefox driver/geckodriver  -jar /path/to/selenium server/selenium-server-standalone-3.0.0.jar
```

Run the project with phpunit
```sh
phpunit Facebook.php
```
