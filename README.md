verosk.acme-sh
==============

This role sets-up [acme.sh][acme] on the target host. It does no
installation of the role.

It's more proof of concept.


Role Variables
--------------

Please check `defaults/main.yml` 

Dependencies
------------

This role has no dependencies.  Weel, the `nc` should be installed on 
target host to start `acme.sh`.

Example Playbook
----------------

    - hosts: webservers
      roles:
         - role: veros.acme-sh

License
-------

BSD || WTFPL

Author Information
------------------

This role was prepared by Věroš Kaplan, 
sponsored by [vpsfree.cz][vpsfree]

[vpsfree]: https://vpsfree.cz
[acme]: https://github.com/Neilpang/acme.sh
