[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-postfix.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-postfix)
---
## IaC: with [Ansible](https://www.ansible.com) role to install and configure [Postfix](http://www.postfix.org/)
------------

Description
------------

 * 

Requirements
------------

 *

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-postfix
...    
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
