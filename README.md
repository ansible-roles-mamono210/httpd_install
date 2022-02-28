[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/httpd_install/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/httpd_install/tree/main)
[![](https://github.com/ansible-roles-mamono210/httpd_install/workflows/build/badge.svg)](https://github.com/ansible-roles-mamono210/httpd_install/actions?query=workflow%3Abuild)

Role Description
=========

Installs [Apache](https://httpd.apache.org) for CentOS7 / CentOS Stream 8.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - httpd_install
```

License
-------

BSD
