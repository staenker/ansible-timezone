staenker.timezone
=========

Sets the timezone of Debian based systems.

Requirements
------------

A Debian based system is enough

Role Variables
--------------

 - timezone, default: UTC, examples: "Europe/Berlin", "Europe/Stockholm", "America/New_York", ...


Dependencies
------------

none

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: staenker.timezone, timezone: Europe/Berlin }

License
-------

Apache License, Version 2.0

Author Information
------------------

Awesome dude
