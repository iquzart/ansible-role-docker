Ansible Docker Role
=========
[![Ansible Galaxy](https://img.shields.io/badge/galaxy-iquzart.docker-blue)](https://galaxy.ansible.com/iquzart/docker)
![Molecule Test](https://github.com/iquzart/ansible-role-docker/workflows/Molecule%20Test/badge.svg?) 
[![License](https://img.shields.io/:license-mit-blue.svg)](https://badges.mit-license.org)


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
