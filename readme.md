#PHP

## Installing PHP

* Open terminal
* Enter the command `mkdir%NAME%` **(name representing the name of the file)**
* Enter the name of the directory
* Enter the command `mkdir php-test`
* Enter the command `sudo apt-get update && apt-get upgrade`
* Enter the command `sudo apt-get install php`
* Enter the command  `php -v`
* Enter the command `sudo apt-get install php-pear php7.2-curl php7.2-dev php7.1 -gd`
* Enter the command `php7.2-mbstring php7.2-zip php7.2-mysql php7.2-xml`
* Enter the command `apt-cache search --names-only ^php`

## Installing composer

* Open terminal
* Enter the command `sudo apt update`
* Enter the command `sudo apt install curl php-cli php-mbstring git unzip`
* Enter the command `cd ..`
* Enter the command `curl -sS https://getcomposer.org/installer -o composer-setup.php`
* Enter the command `sudo php composer-setup.php --install-dir=/user/local/bin --filename=composer`
* Enter the command `composer`
* Enter the command `php-test`
* Enter the command `composer`
* Enter the command `composer require facebook/webdriver`
* Enter the command `ls -al`
* Enter the command `cd vendor`

## Hello World in php

* Open terminal 
* Enter the command `subl .` 
* Make a new file and name it `HelloWorld.php`
* Enter the code 
```
<?php

$str = "Hello world!";
echo $str;
echo "\n";
echo "What a nice day!";

?>


```
* Save the file
* Go back to the terminal
* Enter the command 
```
<?php
	echo 'Hello, World!';
?>

```
* Run the file by writing the command `php %NAME%.php`