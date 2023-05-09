# ansible-playbook-example
install apache2 http server on multiple server by ansible playbook

# please make changes in hosts file by adding all ip addresses of all server in which you want to install Apache http server
192.168.0.11
192.168.0.12

# change ssh user name and password in hosts file
[all:vars]
ansible_user=ubuntu
ansible_ssh_pass=ubuntu
ansible_become_pass=ubuntu
* Change username  and password accordingly 

# Run below command to execute ansible script 
ansible-playbook playbooks/ansible-playbook.yaml
