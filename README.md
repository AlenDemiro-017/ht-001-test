Symfony Demo Application
========================

The "Symfony Demo Application" is a reference application created to show how
to develop applications following the [Symfony Best Practices][1].

Requirements
------------

  * PHP 8.0.2 or higher;
  * PDO-SQLite PHP extension enabled;
  * and the [usual Symfony application requirements][2].

Installation
------------

Clone this repository on your computer and run
this command in the project folder:

```bash
$ composer install
```

If you don't have the Symfony binary installed, run `php -S localhost:8000 -t public/`
to use the built-in PHP web server or [configure a web server][3] like Nginx or
Apache to run the application.

Then access the application in your browser.

Tests
-----

Execute this command to run tests:

```bash
$ cd my_project/
$ ./bin/phpunit
```
> You can run `export SYMFONY_DEPRECATIONS_HELPER=weak` in terminal before running the tests to suppress the deprecation warnings. 

[1]: https://symfony.com/doc/current/best_practices.html
[2]: https://symfony.com/doc/current/reference/requirements.html
[3]: https://symfony.com/doc/current/cookbook/configuration/web_server_configuration.html
[4]: https://symfony.com/download
