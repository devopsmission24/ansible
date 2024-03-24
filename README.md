# Pre-Requisites
Step 1: Install ansible tool

$sudo yum install epel-release

$sudo yum install ansible

# Execution Flow
Step 1: clone Ansible repo
```
git clone https://github.com/devopsmission24/ansible.git && cd ansible
```
Step 2: Run playbook to install all the software packages 
```
ansible-playbook scm.yml
```
