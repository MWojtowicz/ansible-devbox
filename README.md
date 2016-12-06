Role Name
=========

Devbox for PHP developing

Role Variables
--------------

TODO

Dependencies
------------

  - geerlingguy.apache
  - geerlingguy.apache-php-fpm
  - geerlingguy.composer
  - geerlingguy.daemonize
  - geerlingguy.elasticsearch
  - geerlingguy.firewall
  - geerlingguy.git
  - geerlingguy.java
  - geerlingguy.mailhog
  - geerlingguy.mariadb
  - geerlingguy.memcached
  - geerlingguy.nodejs
  - geerlingguy.ntp
  - geerlingguy.php
  - geerlingguy.php-mysql
  - geerlingguy.php-pear
  - geerlingguy.php-pecl
  - geerlingguy.php-redis
  - geerlingguy.php-xdebug
  - geerlingguy.phpmyadmin
  - geerlingguy.pimpmylog
  - geerlingguy.redis
  - geerlingguy.ruby
  - geerlingguy.varnish
  - mwojtowicz.putty
  
Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: mwojtowicz.devbox }

License
-------

MIT