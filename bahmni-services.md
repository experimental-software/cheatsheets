---
title: Bahmni services
category: Bahmni
layout: 2017/sheet
---

## Get the current service status

```
sudo service --status-all
chkconfig --list

sudo service mysqld status
sudo service postgresql-9.2 status
sudo service openmrs status
sudo service httpd status
sudo service bahmni-reports status
sudo service bahmni-lab status
sudo service openerp status
sudo service bahmni-erp-connect status
sudo service atomfeed-console status
sudo service pacs-integration status
```

## Network analysis
### How to find out which ports are openend?
```
yum install nmap
nmap -sT -O localhost
```
See [centos.org](https://www.centos.org/docs/5/html/5.1/Deployment_Guide/s1-server-ports.html)

## Documentation
- [Install Bahmni on CentOS#Bahmni Services](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/33128505/Install+Bahmni+on+CentOS#InstallBahmnionCentOS-BahmniServices)
- [Architecture, RPMs and services in Bahmni](https://bahmni.atlassian.net/wiki/spaces/BAH/pages/114316310/Architecture+RPMs+and+services+in+Bahmni)
