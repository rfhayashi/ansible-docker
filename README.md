Role Name
=========

Installs Docker-Engine on CentOS.

Requirements
------------
None

Role Variables
--------------
    docker_version: 1.12.0
    docker_users: []
    docker_options: 

Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: rfhayashi.docker }

License
-------

MIT
