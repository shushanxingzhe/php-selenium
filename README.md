PHP Selenium
=====

A simple project integrated PHPUNIT,Facebook webdriverd and use Travis CI

[![Build Status](https://travis-ci.org/shushanxingzhe/php-selenium.svg?branch=master)](https://travis-ci.org/shushanxingzhe/php-selenium)
System Requirements
===================

PHP Selenium has the following requirements:

 * PHP version 5.6 or later.
 * Chrome browser
 * [Composer](https://getcomposer.org/)
 * [Selenium Standalone Server](http://www.seleniumhq.org/download/)
 * [Chrome driver](https://sites.google.com/a/chromium.org/chromedriver/)
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

Run Selenium Server with Chrome driver
```sh
java  -Dwebdriver.chrome.driver=/path/to/chromedriver  -jar /path/to/selenium server/selenium-server-standalone-3.0.0.jar
```

Run the project with phpunit
```sh
phpunit Facebook.php
```
