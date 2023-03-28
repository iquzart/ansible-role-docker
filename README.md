Ansible Docker Role
=========
![Molecule Test](https://github.com/iquzart/ansible-role-docker/workflows/Molecule%20Test/badge.svg) 
[![Role Name](https://img.shields.io/ansible/role/52365?label=Role%20Name&logo=ansible&style=flat-square)](https://galaxy.ansible.com/iquzart/docker)
[![Quality Score](https://img.shields.io/ansible/quality/52365?label=Quality%20Score&logo=ansible&style=flat-square)](https://galaxy.ansible.com/iquzart/docker)
[![Role Downloads](https://img.shields.io/ansible/role/d/52365?label=Role%20Downloads&logo=ansible&style=flat-square)](https://galaxy.ansible.com/iquzart/docker)
[![License](https://img.shields.io/:license-mit-blue.svg?style=flat-square)](https://badges.mit-license.org)


Ansible role for docker community edition setup


Support Matrix
--------------
| Distro | Version |
| --- | --- |
| Centos | 8 | 
| Ubuntu |  20.04 LTS | 
| Debian | 10 | 

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
        - iquzart.docker
```

License
-------

MIT


Author Information
------------------

Muhammed Iqbal <iquzart@hotmail.com>
