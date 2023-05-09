# ansible-playbook-example
install apache2 http server on multiple server by ansible playbook

# update ip address of all servers by adding lines in hosts file
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
