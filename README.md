ansible-role-openjdk
============

Use this role to install OpenJDK from zulu ppa.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    openjdk_version: "11"

Example Playbook
----------------

    - hosts: openjdk
      roles:
         - { role: ansible-role-openjdk }

License
-------

MIT

Author Information
------------------

https://github.com/pasernik

Based on https://github.com/andrelohmann/ansible-role-percona_mysql
