# lamp-playbook

## to deploy
```
ansible-galaxy install --role-file=requirements.yml --roles-path=roles/external
ansible-playbook -i inventory/production playbook.yml
```
