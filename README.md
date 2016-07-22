Commuting Compensation Calculator Application
=============================================

The "Commuting Compensation Calculator Application" is a tool to calculate and create a downloadable csv file containing the commuting compensation of employees for each month from the start of current year using employee data from the mysql database.

Requirements
------------

  * PHP 5.3 or higher;
  * and the [usual Symfony application requirements](http://symfony.com/doc/current/reference/requirements.html).

Installation
------------

Download and install the demo application using Git and Composer:

     $ git clone https://github.com/Seldar/symfony2-examinations
     $ cd symfony2-examinations/
     $ composer install --no-interaction

Create a mysql database named `symfony2`. Then Execute `employee.sql` in symfony2 database.

Usage
-----

If you have PHP 5.4 or higher, there is no need to configure a virtual host
in your web server to access the application. Just use the built-in web server:

```bash
$ cd symfony2-examinations/
$ php bin/console server:run
```

This command will start a web server for the Symfony application. Now you can
access the application in your browser at <http://localhost:8000/en/commuting-allowance/getCSV>. You can
stop the built-in web server by pressing `Ctrl + C` while you're in the
terminal.

You can run tests created for the CommutingController class by running `phpunit.phar`:

```bash
php bin/phpunit.phar
```
