# Ansible VM Automation and codeVersion control in docker container.
This repository contains Ansible playbooks and scripts to automate the workload on running VMs in Ubuntu and CentOS environments. The automation includes installing Apache Tomcat, monitoring system workload, and more.

## Problem statement:
Using ansible automante centos and ubuntu server running on the vmware. Continues tracking the code version control. Write playbooks mentioned in userstory.

User Story :

1. Install ansible automation engine in a docker environment. 
2. Configure github and make ansible playbooks version control and use github only for code version control
3. Using one single ansible automate a centos and ubuntu installation based on the variable passed to the playbook 
4. Monitor the visual machines workload 
5. Install apache tomcat, find the top 5 CPU utilizing process on a server, remotely accessible vm’s



## Prerequisites
- Docker
- Git
- Ansible
- 1 or more vm's installed on vmware ->
  // in this project we choosen centos and ubuntu.


