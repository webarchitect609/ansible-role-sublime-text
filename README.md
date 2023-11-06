Ansible Role: Sublime Text
==========================


[![Build Status](https://github.com/webarchitect609/ansible-role-sublime-text/actions/workflows/build.yml/badge.svg)](https://github.com/webarchitect609/ansible-role-sublime-text/actions/workflows/build.yml)
[![Latest version](https://img.shields.io/github/v/tag/webarchitect609/ansible-role-sublime-text?sort=semver)](https://github.com/webarchitect609/ansible-role-sublime-text/releases)
[![Downloads](https://img.shields.io/ansible/role/d/30622)](https://galaxy.ansible.com/ui/standalone/roles/webarchitect609/sublime_text)
[![License](https://img.shields.io/github/license/webarchitect609/ansible-role-sublime-text)](LICENSE.md)
[![More stuff from me](https://img.shields.io/badge/galaxy-webarchitect609-000)](https://galaxy.ansible.com/ui/standalone/namespaces/7493/)

Installs [Sublime Text](https://www.sublimetext.com/) from the official repository.

Requirements
------------

None.

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - { role: webarchitect609.sublime_text }
```

License & Author Information
----------------------------

[BSD-3-Clause](LICENSE.md)
