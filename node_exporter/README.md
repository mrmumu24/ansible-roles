# Node exporter
An ansible role which installs and configures node exporter 1.0.0.

## Requirements
RHEL family\
ansible: 2.10.4\
python: 3.9

## Role Variables
See defaults for the complete list.

## Example playbook
```
- name: install and configure node exporter service
  hosts: all
  roles:
    - node_exporter
```
