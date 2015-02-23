# taloLogger-playbook
Ansible playbook for installing olammi's taloLogger and configuring data sources.
Development and testing done on vanilla Debian squeeze running on Sun Netra T105.

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
