# taloLogger-playbook
Ansible playbook for installing olammi's taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC) with latest ansible available from pip.

Implemented:
 - Download of taloLogger packages
 - Installation of MySQL datastore
 - Installation of taloLogger
 - Uptime data source configuration
 - Installation of taloLoggerGraph, initially for dummy data 

To-do:
 - Installation of other datastores
 - Configuring serial I/O data source
 - Configuring graphs for additional data sources
 - sudo
 - nginx
 - Partition to role(s) instead of single playbook
