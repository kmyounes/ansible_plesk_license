Plesk License
=========
This role will help administrator to update plesk key to they server with possibility to enable provider view in plesk Dashboard.


Requirements
------------



Role Variables
--------------

- license_key_virtual : License key for virtualized servers
- license_key_physical : License key for bare metal servers

Dependencies
------------


Example Playbook
----------------

Example of usage

  hosts: all
  vars:
    - license_key_virtual : "A00500-A00500-A00500-A00500-A00500"
    - license_key_physical : "A00T00-A00T00-A00T00-A00T00-A00T00"
  roles:
    - { role: plesk-license }
  

Hosts groups are:
[virtual]



[physical]


[provider_view]


License
-------

Apache

Author Information
------------------

