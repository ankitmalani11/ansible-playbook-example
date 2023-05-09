# ansible-playbook-example
install apache2 http server on multiple server by ansible playbook

# please make changes in hosts file by adding all ip addresses of all server in which you want to install Apache http server
192.168.0.11 <br />
192.168.0.12 <br />

# change ssh user name and password in hosts file
[all:vars] <br />
ansible_user=ubuntu <br />
ansible_ssh_pass=ubuntu <br />
ansible_become_pass=ubuntu <br />
* Change username  and password accordingly  <br />

# Run below command to execute ansible script 
ansible-playbook playbooks/ansible-playbook.yaml
