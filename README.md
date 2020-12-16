Ansible Docker Role
=========

![Molecule Test - Master](https://github.com/iquzart/ansible-role-docker/workflows/Molecule%20Test/badge.svg?) ![Molecule Test - Development](https://github.com/iquzart/ansible-role-docker/workflows/Molecule%20Test/badge.svg?branch=development)


Ansible role for docker community edition setup


Features
---------
```
  1. Support CentOS, Ubuntu, Debian.
  2. Create a user account with docker access.
```
Role Variables
--------------

| Variable | Description |
| --- | --- |
| user_name | Account to manage docker | 
| user_comment |  Description for the account | 
| user_password | Account password (clear text) | 


Example Playbook
----------------
```
    - hosts: servers
      roles:
        - ansible-role-docker
```

To-Do
------
```
1. Docker Compose
2. Docker Logs
```

License
-------

MIT

Author Information
------------------

Muhammed Iqbal <iquzart@hotmail.com>
