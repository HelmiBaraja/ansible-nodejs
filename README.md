Role Name
=========

nodejs

Requirements
------------

This is tested using vagrant and VMWare running on RHEL 7.4

ansible 2.2

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

N/A

Example Playbook
----------------

- Command 
`ansible-playbook -i <hosts> <yaml file>`

- sample, Install all url to install nodejs
ansible-playbook -i hosts site.yml

- To deploy new code
ansible-playbook -i hosts site.yml --tags "deploy"

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
