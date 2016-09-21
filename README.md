Role Name
=========

Installs Docker-Engine on CentOS.

Requirements
------------

Role Variables
--------------

Available variables are listed below, along with default values:

    docker_version: 1.12.0
    docker_users: []

Dependencies
------------

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rfhayashi.docker }

License
-------

MIT
