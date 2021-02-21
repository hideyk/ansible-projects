# Ansible for ELK stack deployment

## Ansible Elasticsearch role
An Ansible role that installs Elasticsearch on RedHat/CentOS or Debian/Ubuntu.

## Requirements
Requires at least Java 8. You may use geerlingguy.java to easily install Java.

## Example playbook
    - hosts: search
      roles: 
        - geerlingguy.java
        - hideyukikanazawa.elk