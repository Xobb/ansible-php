Xobb.php
========

PHP fpm and cli interface for your web server

Requirements
------------

Not much.

Role Variables
--------------

Very few variable by default:

    php_timezone: Europe/Kiev
    php_install_dev: false
    php_fpm_listen: /var/run/php/php7.0-fpm.sock
    php_packages: [php7.0-fpm, php7.0-cli, php7.0-intl, php7.0-gd, php-mbstring ,php7.0-curl, php7.0-xml, php-zip]

Dependencies
------------

None. Works well with [geerlingguy.nginx](https://github.com/geerlingguy/ansible-role-nginx).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: webservers
      roles:
         - { role: xobb.php, php_timezone: America/Caracas }

License
-------

BSD
