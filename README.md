# ansible-role-nodejs [![Build Status](https://secure.travis-ci.org/davehorton/ansible-role-nodejs.png)](http://travis-ci.org/davehorton/ansible-role-nodejs)

This is an ansible role for building nodejs. 

## Role variables

Available variables are listed below, along with default values (see defaults/main.yml):

```
nodeVersion: 10.15.3
```
The nodejs version to install.

## Example playbook
```
---
- hosts: all
  become: yes
  roles:
    - ansible-role-nodejs
```
