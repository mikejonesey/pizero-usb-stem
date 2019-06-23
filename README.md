Role Name
=========

A simple role to setup the raspberry pi zero with usb.

Requirements
------------

Install raspian on sdcard, and mount it somewhere.

Role Variables
--------------

pizero_mount_point = the mount point of the raspian sdcard.

Dependencies
------------

none.

Example Playbook
----------------

- hosts: localhost
  become: yes
  roles:
    - pizero-usb-stem
  tags: pizero

License
-------

BSD

Author Information
------------------

mike.
