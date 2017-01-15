# ansible-role-glpi
Ansible role to install glpi (http://glpi-project.org/)

## TODO
- create database
- handle updates
- handle plugins installation

## Installation
In your playbook create a file requirements.yml:
```
- src: git+https://github.com/cbrandel/ansible-role-glpi
```
and execute:
```ansible-galaxy install -r requirements.yml```
