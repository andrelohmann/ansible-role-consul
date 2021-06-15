consul
======

[![Build Status](https://travis-ci.org/andrelohmann/ansible-role-consul.svg?branch=master)](https://travis-ci.org/andrelohmann/ansible-role-consul)

Use this role to install consul.

Requirements
------------

This role requires ubuntu.

Role Variables
--------------

    consul_version: 1.9.6 #defaults to 'latest'

Example Playbook
----------------

    - hosts: consul
      roles:
         - andrelohmann.consul

License
-------

MIT

Author Information
------------------

https://github.com/andrelohmann
