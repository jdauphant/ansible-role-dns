ansible-roles-dns
=================

Ansible host for configure DNS

# Examples :
```
-  host: all
   role : dns
   dns_domain: localdomain
   dns_nameservers: ['127.0.0.1', '8.8.8.8']

-  host: all
   role : dns
   dns_nameservers: ['8.8.8.8']  
   dns_searchs: "localdomain otherdomain"

```
