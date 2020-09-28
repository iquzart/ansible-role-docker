Ansible Docker Engine
=========

Ansible role for docker community edition setup


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
