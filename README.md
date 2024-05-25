Role Name
=========

Ansible role to install/manage
    https://github.com/fboender/multi-git-status
on serveral linux distros

Requirements
------------

deploy host has ansible and ansible-galaxy installed.
Root access to target host

Role Variables
--------------

- *bindir*: path where executable is installed, set to /usr/local/bin
- *man1dir*: path where manpage is installed, set to /usr/share/man/man1

Dependencies
------------

git

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT

Author Information
------------------

    ARK-ICT
    Andre Rikkert de Koe - ICT
