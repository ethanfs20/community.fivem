Role Name
=========

Easily deploy FiveM servers to managed nodes.

Requirements
------------

FiveM, GIT, and WGET.

Role Variables
--------------

user_name: The name of the user to create.
create_user: true or false, if we should create a user.
home_dir: Directory path of the created user.
target_directory: The directory of the FiveM install folder.
package_url: The url of the server build NOT resources.
package_name: Name of the package when it downloads. (fx.tar.xz)
repo_url: Resource file for default files. https://github.com/citizenfx/cfx-server-data.git

Dependencies
------------

FiveM, GIT, and WGET.

Example Playbook
----------------

---
- name: FiveM configuration
  hosts: all
  role:
    - fivem

License
-------

MIT

Author Information
------------------

Ethan Shearer https://github.com/ethanfs20/community.fivem