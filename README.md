# about ansible-templates
Template repository for Ansible.

You can choose between:
* non-multi-environment 
* multi-environment


# How to call non-multi-environments
```
ansible-playbook yourPlaybook.yml
```

# How to call multi-environment plays
``` 
ansible-playbook -i inventories/development yourPlaybook.yml
```
