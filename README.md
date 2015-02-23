# taloLogger-playbook
Ansible playbook for installing olammi's taloLogger and configuring data sources.
Tested to work on Debian squeeze (SPARC) with latest ansible available from pip.

Implemented:
 - Download of taloLogger packages
 - Installation of (MySQL) datastore
 - Installation of taloLogger
 - Configuring of uptime data source

To-do:
 - Installation of taloLoggerGraph
 - Installation of other datastores
 - Configuring of other data sources
 - sudo
 - Partition to role(s) instead of single playbook
