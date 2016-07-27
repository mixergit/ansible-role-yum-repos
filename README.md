Ansible Role: yum repository
=========

[![Build Status](https://travis-ci.org/officel/ansible-role-yum-repos.svg?branch=master)](https://travis-ci.org/officel/ansible-role-yum-repos)
[![Ansible Role](https://img.shields.io/badge/galaxy-officel.yum--repos-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/officel/yum-repos/)

install yum repository(s).

Requirements
------------

none.

Role Variables
--------------

see defaults/main.yml

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
         - officel.yum-repos

License
-------

MIT / BSD

Author Information
------------------

This role was created by raki.
