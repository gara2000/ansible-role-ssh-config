SSH Configuration role
=========

This role configures SSH on the target server to be more secure

Requirements
------------

- Runs on: Debian based distros

Role Variables
--------------

ssh_port [default: 22]: the SSH port number

Dependencies
------------

No dependencies

Example Playbook
----------------

```bash
- hosts: servers
  become: yes
  roles:
      - gara2000.ssh-config
```

License
-------

BSD
