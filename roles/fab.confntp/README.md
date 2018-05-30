Role Name
=========

This role install and configure ntpd to use a local network time server.
The configuration is really basic (see stdntp.conf in template folder)

Requirements
------------

A network time server

Role Variables
--------------

ntpserver: address or fqdn of the local ntp server
timezone: the time zone (see https://en.wikipedia.org/wiki/List_of_tz_database_time_zones for list)

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: fab.confntp }

License
-------

GPLv3

Author Information
------------------

Fabrice LEGRAND, computer engineer
https://fabsystem.wordpress.com/
https://github.com/fab-system

