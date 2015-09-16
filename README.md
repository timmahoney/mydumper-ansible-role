MyDumper
=========

Ansible role to install [MyDumper](https://launchpad.net/mydumper) on Centos.

Installs version 0.6.2.

Requirements
------------

The role takes care of installing everything.

Role Variables
--------------

mydumper_major_version: "0.6"
mydumper_minor_version: "0.6.2"

Example Playbook
----------------

- hosts: servers
  roles:
     - mydumper

License
-------

GPLv2

Author Information
------------------

Timothy Mahoney
https://github.com/timmahoney
http://timothymahoney.com
