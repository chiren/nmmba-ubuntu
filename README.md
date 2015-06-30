# nmmba-ubuntu

------------------------

Ansible playbook for intalling NMMBA stacks on an Ubuntu 14.04 Server

*These playbooks require Ansible 1.8.1.*

The inventory file *hosts* defines the nodes in which the stacks should be configured.

```
        [host_group]
        host
```

The stack can be deployed using the following
command:

```
        ansible-playbook -i hosts site.yml 
```

