Build a simple LAMP stack using Ansible.

Requirements:
- Ansible 2.0+
- CentOS 7

These playbooks are a simple starter's guide to building a LAMP stack. The playbook(s) 
were tested on CentOS 7.x only, this far.

The inventory file 'hosts' defines only a couple of nodes for test purposes:

        [lampservers]
        192.168.1.97
        192.168.1.98
