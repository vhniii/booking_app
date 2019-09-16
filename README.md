# Booking App

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Needed software in your computer to run this software:

* php
```
sudo apt-get install php7.0-cli
sudo apt-get install php-xml
```

* [composer](https://getcomposer.org/download/)

* SQLite
```
sudo apt-get install php-sqlite3
```

### Installing

To install the software you have following options:

Cloning the project to your computer. If you have ssh access.

```
git glone git@gitlab.com:i-sepp/bcs-koolitus.git
```

Or download it manually from the gitlab [page](https://gitlab.com/i-sepp/bcs-koolitus).

Then you need to have composer installed in your computer.
And then you need to install composer packages in your project folder.
```
composer install
```

## Testing

You can test by starting server and going to the following url:
```
symfony server:start
URL: localhost:8000/bookings/create
```

## Built With

* [Symfony](https://symfony.com/) - The web framework used
* [Composer](https://getcomposer.org/) - Dependency Management
* [Twig](http://twig.sensiolabs.org/) - Php template engine
* [Doctrine DBAL](http://docs.doctrine-project.org/projects/doctrine-dbal/en/latest/index.html) - Database connection
* [PHPUnit](https://phpunit.de/) - PHP testing framework


## License

This project is licensed under the MIT License.
