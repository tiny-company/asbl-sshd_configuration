# asbl-sshd_configuration

## Description

ansible playbook role to configure sshd service 

## Prerequisite

- None 

## Usage
 
### Use role

- Add the role git source in "requirements.yml" file :
```
  - name: role_name
    scm: git
    src: https://github.com/tiny-company/<repository_name>.git
    version: main  
```

- And then use the galaxy command to load the file dependencies :
```
ansible-galaxy install -r requirements.yml
```

- Or manually get the playbook as collection (with ansible-galaxy) :
```
ansible-galaxy collection install https://github.com/tiny-company/<repository_name>.git
```

### Variables

For an exhaustive list of variables check the [defaults](defaults/main.yml)
file. Ideally, all values will have commentaries describing what are their
purposes and by the default value you can tell the type.


## Source :

- [dev-sec ansible ssh hardening playbook](https://github.com/dev-sec/ansible-ssh-hardening/tree/master)
- [arillso ansible sshd playbook](https://github.com/arillso/ansible.sshd)
- [DO1JLR ansible sshd playbook](https://github.com/roles-ansible/ansible_role_sshd/tree/15b7867a37e4036947de29c727075c4a75859e43)
- [ansible facts var](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_vars_facts.html)
- [ascii art for motd](https://texteditor.com/ascii-art/)

