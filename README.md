# lamp-playbook

## to deploy
```
ansible-galaxy install --role-file=requirements.yml --roles-path=roles/external
ansible-playbook -i inventory/production playbook.yml
```

## Kown Issue
* You have to login and install this required module:
```
sudo apt-get install libapache2-mod-php
```
