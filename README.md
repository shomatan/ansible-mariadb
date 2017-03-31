Ansible role: MariaDB
=========

[![Build Status](https://travis-ci.org/shomatan/ansible-mariadb.svg?branch=master)](https://travis-ci.org/shomatan/ansible-mariadb)

Installs and configures MariaDB.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
        - { role: shomatan.mariadb }
      tasks:
        - name: Run MariaDB backup tasks.
          include_role:
            name: shomatan.mariadb
            tasks_from: backup
            private: true

License
-------

MIT

Author Information
------------------
