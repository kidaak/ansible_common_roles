Role mysql-server
=================

Use this role to setup a mysql server

Variables
---------

- root_mysql_password: optional, default to ""

Example Playbook
----------------

    - hosts: servers
      roles:
         - mysql-server
