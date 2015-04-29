# Trever for EC2

Trever is a self-hosted, web-based, automated snapshot manager for the Amazon Web Services EC2 platform.

---
**What can Trever do automatically?**

- Create new snapshots of EC2 volumes
- Delete old snapshots
- Rotate snapshots based on commonly used backup techniques *(First In, First Out, Grandfather-father-son, Tower of Hanoi...)*
- Rotate snapshots based on custom schedules

Trever tries to make it easy to manage snapshots for one or more EC2 accounts. 

Trevor is built on [Laravel 5](https://github.com/laravel/laravel) and integrates various packages like [AWS SDK for PHP](https://github.com/aws/aws-sdk-php-laravel).

### Installation
----
You will need [Composer](https://getcomposer.org/) installed to properly install Trever.

From the base directory of Trever, run:
```sh
$ composer install
```
### 

### Projects & Packages
----
Trever is built using a number of open-source projects:

* [Laravel 5](https://github.com/laravel/laravel)
* [jQuery](https://jquery.com)

Trever is currently extended with the following packages

* [AWS SDK for PHP for Laravel 5](https://github.com/aws/aws-sdk-php-laravel)

### License
----

[GPLv3 License](http://www.gnu.org/licenses/gpl-3.0.html)
