[![](https://github.com/ansible-playbooks-centos7/redmine_install/workflows/build/badge.svg)](https://github.com/ansible-playbooks-centos7/redmine_install/actions?query=workflow%3Abuild)
[![CircleCI](https://circleci.com/gh/ansible-playbooks-centos7/redmine_install.svg?style=svg)](https://circleci.com/gh/ansible-playbooks-centos7/redmine_install)


This playbook installs Redmine on CentOS7.

## Install Redmine

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```
