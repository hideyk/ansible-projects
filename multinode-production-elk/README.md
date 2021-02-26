# Ansible for ELK stack deployment
Ansible playbook that deploys a multi-node ELK cluster

## Requirements
Requires at least Java 8. You may use geerlingguy.java to easily install Java.

## Example playbook
    - hosts: search
      roles: 
        - geerlingguy.java
        - hideyukikanazawa.elk

## Execution
    ansible-playbook -i hosts --ask-become-pass site.yml