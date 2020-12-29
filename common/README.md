# Docker
An ansible role which installs some useful packages and updates all packages.

## Requirements
RHEL family\
ansible: 2.10.4\
python: 3.9

## Role Variables
See defaults for the complete list.

## Example playbook
```
- name: install some useful packages then updates all packages
  hosts: all
  gather_facts: false
  roles:
    - common
```
