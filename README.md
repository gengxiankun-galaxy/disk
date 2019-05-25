DISK
=========
Format the disk and mount it via ansible

Role Variables
--------------

parameter | description
------------ | -------------
DISK | disk name
DISK_PARTITION | disk partition
DISK_MOUNT_DIR | mounted directory
DISK_FSTYPE | file format

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: disk }

License
-------

BSD
