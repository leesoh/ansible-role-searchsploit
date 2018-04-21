Role Name
=========

Ansible role to install the Exploit Database.

Requirements
------------

None

Role Variables
--------------

  searchsploit_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

To begin:

  - hosts: servers
    roles:
        - { role: leesoh.searchsploit }

License
-------

BSD

Author Information
------------------

Exploit Database: https://www.exploit-db.com/searchsploit/
