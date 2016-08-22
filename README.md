mamercad.cachet
===============

Sets up the [Cachet](https://cachethq.io/) on CentOS/RHEL 7.x with MySQL, Redis, Apache 2.4 and PHP 5.5

Requirements
------------

- Fedora EPEL (for Redis)
- Redhat Software Collections (for Apache 2.4 and PHP 5.5)

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - cachet
      roles:
          mamercad.epel
        - mamercad.cachet

Warnings
--------

This role puts SELinux into permissive mode

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
