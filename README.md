ansible-role-dns
================

Ansible role for configure DNS

# Examples :
```
- hosts: all
  roles: 
  - role: ansible-role-dns
    dns_domain: localdomain
    dns_nameservers: ['127.0.0.1', '8.8.8.8']

- hosts: all
  roles:
  - role: ansible-role-dns
    dns_nameservers: ['8.8.8.8']  
    dns_searchs: "localdomain otherdomain"

```
