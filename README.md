DISK
=========
Format the disk and mount it via ansible

Installation
------------

`ansible-galaxy install gengxiankun.disk`

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
         - gengxiankun.disk

License
-------

BSD

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
