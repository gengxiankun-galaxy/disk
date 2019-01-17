DISK
=========

Role Variables
--------------

parameter | description
------------ | -------------
DISK | 磁盘
PARTITION | 磁盘分区
MOUNT_DIR | 挂在目录

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: disk }

License
-------

BSD
