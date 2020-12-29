# Docker
An ansible role which installs latest docker.

## Requirements
RHEL family\
ansible: 2.10.4\
python: 3.9

## Role Variables
See defaults for the complete list.

## Example playbook
```
- name: install docker
  hosts: docker
  gather_facts: false
  roles:
    - docker
```
