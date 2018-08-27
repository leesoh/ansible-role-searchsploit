Role Name
=========

Install the Exploit Database.

Requirements
------------

None

Role Variables
--------------

  searchsploit_git_location: '/opt'

Dependencies
------------

* `leesoh.git`

Example Playbook
----------------

```yml
  - hosts: servers
    roles:
        - leesoh.searchsploit
```

License
-------

BSD

Author Information
------------------

Exploit Database: https://www.exploit-db.com/searchsploit/
