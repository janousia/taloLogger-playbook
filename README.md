# taloLogger-playbook

Ansible playbook for installing olammi's taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC) with latest ansible available from pip.

#Role dependencies:

https://github.com/janousia/taloLogger-role

# Usage

1) Set up inventory.txt host(s) and related connectivity (e.g. ssh keys)

2) Install role dependencies 

`
ansible-galaxy install -r requirements.yml
`

3) Run playbook (overriding role variables where necessary)

`
ansible-playbook -i inventory.txt taloLogger.yml -e MYSQL_ROOT_PASS=non_default
`
