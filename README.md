# taloLogger-playbook

Ansible playbook for installing olammi's taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC) and Raspbian (ARM) with latest ansible 
available from pip.

# Dependencies:

- https://github.com/janousia/taloLogger-role

# Usage

1) Add host(s) to inventory.txt. Example uses local connection and presumes
   passwordless sudo. For remote target(s) you also need to set up ssh keys.

2) Install role dependencies 

`
ansible-galaxy install -r requirements.yml
`

3) Run playbook

`
ansible-playbook -i inventory.txt taloLogger.yml
`
