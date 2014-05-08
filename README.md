Role Name
========

[![Build Status](https://drone-opsdev.rax.io/github.com/rack-roles/mysql/status.svg?branch=master)](https://drone-opsdev.rax.io/github.com/rack-roles/mysql)

This is a basic role to install and configure MySQL.

Requirements
------------

No external requirements.

Role Variables
--------------

* `mysql_bind_address` Defaults to 127.0.0.1
* `mysql_port` Defaults to 3306
* `mysql_root_password` Set this value to a new value. Defaults to changeme123.

Dependencies
------------


Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: Rackspace_Automation.mysql, x: 42 }

License
-------

BSD

Author Information
------------------

[Rackspace - the open cloud company](http://rackspace.com)

Ask about our DevOps Automation Service - [www.rackspace.com/devops](http://rackspace.com/devops)
