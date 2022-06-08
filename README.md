# Symfony 6 Registration and Login System

Symfony 6 Login and Registration System with email verification and reset password abilities.

made in the following video https://www.youtube.com/watch?v=bvhHsutKZek&t=446s

## Requirements
- php 8
- composer
- symfony
- database
- email smtp credentials

## Installation

- add the database credentials to the .env file
- add the mail-smpt credentials to the .env file
- `composer install`
- `php bin/console doctrine:schema:create`
- `symfon serve`


## Commands used to create this project:
`composer create-project symfony/skeleton symfony_login`

`cd symfony_login`

`composer require twig orm security mailer form validator maker symfonycasts/reset-password-bundle symfonycasts/verify-email-bundle`

`php bin/console make:user`

`php bin/console make:auth`

`php bin/console make:registration-form`

`php bin/console make:reset-password`

`php bin/console doctrine:schema:create`

`symfony serve`
