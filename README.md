Build a simple LAMP stack using Ansible.

Requirements:
- Ansible 2.0+
- CentOS 7

These playbooks are a simple starter's guide to building a LAMP stack. The playbook(s) 
were tested on CentOS 7.x only, this far.

The inventory file 'hosts' defines only a couple of nodes for test purposes:

        [lampservers]
        192.168.1.97 ansible_port=2201

Notes:
- secure_ssh.yml (under the `pre_installation` role) disables root login, changes the SSH port (to `2201`)
- a test user (called `testuser1`) was already created and has `sudo` privileges on the remote server
