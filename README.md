# Mari's Books - April 22, 2016

A bookstore website

## By Marika Allely

## Description

This Drupal application allows for authenticated users known as "reviewers" to create their own book review, edit it and delete it. Anonymous users have the ability to view all contents of the site except a coupon code.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Composer](https://getcomposer.org/)
* [MAMP](https://www.mamp.info/en/)

## Installation

* `git clone https://github.com/MBAllely/bookstore.git`
* change into the new directory
* Start up mamp and point servers to main directory
* Go to localhost:8888/phpmyadmin in browser and import `bookstore.sql.zip` DB found in bookstore/sites/DB-Backup
* Create DB username `bookstore` with password `password`
* Go to localhost:8888 to view Drupal project.

## Databases Used
* `bookstore`

## Usernames and Passwords
* DB: `bookstore:password`
* Drupal site maintenance account: `admin:password`
* Reviewer user: `Reviewer:password`

## Running / Development

* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

## License

This software is licensed under the MIT license.
Copyright (c) 2016 _**Marika Allely (Her Kingdom Come)**_.
