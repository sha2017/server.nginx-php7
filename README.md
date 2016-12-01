Role Name
=========

server.nginx-php7, Installs nginx and php7, with redis-server from the dotdeb repository on the destination
Also installs memcached

Requirements
------------

Just make sure Ansible has access.

Example Playbook
----------------

  - hosts: all
    roles:
      - server.nginx-php7

License
-------

BSD

Author
------
Peter Tambach, piele@sha2017.org
