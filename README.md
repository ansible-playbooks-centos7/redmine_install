This playbook installs Redmine on CentOS7.

## Install Redmine

Change to root and execute commands below.

```
ansible-galaxy install -r requirements.yml
ansible-playbook -i localhost, -c local install.yml
```


