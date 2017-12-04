Ansible-Role-Epel
=========

Install Vesta control Panel on Centos.

Traditionally Vestacp Install Php 5.* but this role install PHP72 along with PHP-FPM.

Prerequests
-----------

- This role need remo You can use [Ansible-Role-Remi](https://github.com/Rahulsharma0810/Ansible-Role-Remi)

Varibles
-----------
```
PHP_Packages:
  - php72-php
  - php72-php-pear
  - php72-php-bcmath
  - php72-php-pecl-jsond-devel
  - php72-php-mysqlnd
  - php72-php-gd
  - php72-php-common
  - php72-php-fpm
  - php72-php-intl
  - php72-php-cli
  - php72-php
  - php72-php-xml
  - php72-php-opcache
  - php72-php-pecl-apcu
  - php72-php-pecl-jsond
  - php72-php-pdo
  - php72-php-gmp
  - php72-php-process
  - php72-php-pecl-imagick
  - php72-php-devel
  - php72-php-mbstring
  - php72-php-pecl-zip.x86_64
```
```
vesta_email: you@email.com
vesta_password: Password
```
you should use ansible vault for confidentials informations, And obviously you should change default password.

Example Playbook
----------------

    - hosts: YOUR-HOST-OR-GROUP
      roles:
    	- Ansible-Role-VestaCP

License
-------
MIT

Author - Rahul Sharma
------------

[Github](https://github.com/Rahulsharma0810)

[Facebook](https://www.facebook.com/rahulsharma0810)