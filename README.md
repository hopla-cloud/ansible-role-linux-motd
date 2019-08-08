Role Name
=========

Configure motd for hopla.cloud linux system

Requirements
------------

None.

Role Variables
--------------

No variables

Dependencies
------------

- hoplacloud.linux_update

Example Playbook
----------------

    - hosts: localhost
      remote_user: root
      roles:
         - hoplacloud.linux_motd

License
-------

GPLv3

Author Information
------------------

This role was created in 2019 by [hopla.cloud](https://hopla.cloud)
