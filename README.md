Role Name
=========

PostgreSQL role

Role Variables
--------------

postgresql_version: version of postgresql to install

Dependencies
------------

meka.common

Example Playbook
----------------

Role requires you to include it's pre_tasks:

    - hosts: servers
      pre_tasks:
         - include: /etc/ansible/roles/meka.postgresql/pre_tasks/main.yml

License
-------

GPLv3
