Role Name
=========

This role can install vector and connect to clickhouse

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

|vars|description|
|----|-----------|
|vector_version|Version of Vector to install|
|db_name|Clickhouse DB name|
|table_name|Clickhouse table name|

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector-role }


Author Information
------------------

Ewgenij Ostrowskij
