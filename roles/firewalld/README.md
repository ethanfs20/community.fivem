Role Name
=========

Easily configure Firewalld for SSH and FiveM.

Requirements
------------

Firewalld

Role Variables
--------------

ssh_port: The port you use for SSH.
server_port: The port you use for the server.
txadmin_port: The port you use for TxAdmin.

Dependencies
------------

Firewalld

Example Playbook
----------------

---
- name: Firewalld FiveM configuration
  hosts: all
  role:
    - firewalld

License
-------

MIT

Author Information
------------------

Ethan Shearer https://github.com/ethanfs20/community.fivem