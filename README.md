staenker.timezone
=========
[![Ansible Galaxy](http://img.shields.io/badge/AnsibleGalaxy-staenker.timezone-blue.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2119)

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
