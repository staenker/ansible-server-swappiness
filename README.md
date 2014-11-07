Role Name
=========

Set swappiness to 0 so server will only swap if running out of memory. A
monitoring check should verify that 0 bytes of swap are used when running
in production.

Requirements
------------

A Debian based system is enough

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: staenker.server-swappiness }

License
-------

Apache License, Version 2.0

Author Information
------------------

Awesome dude
