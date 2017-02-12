# taloLogger-playbook

Ansible playbook for installing taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC), jessie (x86) and Raspbian (ARM)
with latest ansible available from pip.

# Dependencies:

- https://github.com/janousia/taloLogger-role

# Usage

1) Add host(s) to inventory.txt
2) Install role dependencies 

`
ansible-galaxy install -r requirements.yml
`

3) Run playbook

`
ansible-playbook -i inventory.txt site.yml
`
