verosk.acme-sh
==============

This role sets-up [acme.sh][acme] on the target host. The role does not generate any certificates (yet).

It's started as proof of concept but I've found myself to use it for more
than two years. 


Role Variables
--------------

Please check `defaults/main.yml` 

Dependencies
------------

This role has no dependencies.  But `nc` should be probably installed on 
the target host to start `acme.sh`. 

Example Playbook
----------------

    - hosts: webservers
      roles:
         - role: VerosK.acme-sh

License
-------

BSD-2 || WTFPL

Author Information
------------------

This role was prepared by Věroš Kaplan, 
sponsored by [vpsfree.cz][vpsfree]

[vpsfree]: https://vpsfree.cz
[acme]: https://github.com/Neilpang/acme.sh
