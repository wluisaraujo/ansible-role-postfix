[![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-MailServer-blue.svg)](https://galaxy.ansible.com/wluisaraujo/postfix) [![Build Status](https://travis-ci.org/wluisaraujo/ansible-role-postfix.svg?branch=master)](https://travis-ci.org/wluisaraujo/ansible-role-postfix)
---
## IaC: with [Ansible](https://www.ansible.com) role to install and configure [Postfix](http://www.postfix.org/)
------------

Description
------------

 * 

Requirements
------------

 *

Installation
------------

```console
vagrant@localhost:~$ ansible-galaxy install wluisaraujo.postfix
vagrant@localhost:~$ ansible-galaxy install -r wluisaraujo.postfix/requirements.txt
```

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
    - postfix
...
```

----------------
[![Licence](https://img.shields.io/badge/License-GPL%20v3-red.svg)](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
