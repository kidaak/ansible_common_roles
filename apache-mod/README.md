Role apache-mod
===============

Use this role to setup apache module, such as mod_wsgi, mod_python, etc.

Variables
---------

module_name: required. Module name without "mod_" prefix. For instance, it
  should be set to "wsgi" if you want to enable mod_wsgi.

Dependencies
------------

It depends on role "webserver-apache".

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: apache-mod, module_name: wsgi }
