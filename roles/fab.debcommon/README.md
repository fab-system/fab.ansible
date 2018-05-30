Role Name
=========

This role install some base tools packages for debian or ubuntu 

Requirements
------------

none

Role Variables
--------------

proxy: the fqdn of the proxy to use

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: fab.debcommon, proxy: "http://myproxy:3128/" }

License
-------

GPLv3

Author Information
------------------

Fabrice LEGRAND, computer engineer
https://fabsystem.wordpress.com/
https://github.com/fab-system

