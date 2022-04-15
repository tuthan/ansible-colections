Role Name
=========

This is configuratio of rsyslog server. 
- Basic config
- Support remote log 
- Support tls

Requirements
------------

Tested on debian, not guarantee it will works on other distros

Role Variables
--------------
For more info please check vars folder.
- enable_receiver --> default no. Yes to turn recieve log from remote
- enable_remote_rules --> default no. Yes to enable custom rules. Please edit rule arcordingly
- enable_tls --> default no. Yes to enable tls


Dependencies
------------

N/a

Example Playbook
----------------

    - hosts: log-servers
      roles:
       - rsyslog

License
-------

BSD

Author Information
------------------
- Hung Vo
- https://atas.tech
