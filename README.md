# taloLogger-playbook

Ansible playbook for installing olammi's taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC) with latest ansible available from pip.

# Dependencies:

- https://github.com/janousia/taloLogger-role

# Usage

1) Add inventory.txt host(s) and set up related connectivity (e.g. ssh keys + passwordless sudo)

2) Install role dependencies 

`
ansible-galaxy install -r requirements.yml
`

3) Run playbook (overriding role variables where necessary)

`
ansible-playbook -i inventory.txt taloLogger.yml -e MYSQL_ROOT_PASS=non_default
`
