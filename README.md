# Aspect Oriented Programming in PHP

The purpose of this project is to demonstrate the use of aspect-oriented programming in PHP using Go!. Go! is a PHP framework that allows us to use aspect-oriented programming using Doctrine Annotations.

This project has three examples of using AOP in PHP:

- The transaction manager;
- The exception logger;
- The profiler.

All implementations of aspects are covered by tests.

# How to run this projecto

## Using Vagrant

Enter the root directory of the project and run `vagrant up`.

## Using Docker Compose

Enter the root directory of the project and run `docker-compose up`.

## Using PHP Built-in web-server

Enter the root directory of the project and run `php -S localhost:8000 -t public/`.
