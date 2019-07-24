Ansible Role: Sublime Text
=========

[![Build Status](https://travis-ci.org/webarchitect609/ansible-role-sublime-text.svg?branch=master)](https://travis-ci.org/webarchitect609/ansible-role-sublime-text)

Installs Sublime Text from the official deb repository.

Requirements
------------

None.

Role Variables
--------------

None of the variables need to be altered for installing the latest stable version of the application. 
However, all available variables are listed below, along with default values (see `defaults/main.yml`):

    sublime_package: sublime-text
    
Package name to install
    
    sublime_deb_source: "deb https://download.sublimetext.com/ apt/stable/"
    
Repository url.
    
    sublime_gpg_key_url: "https://download.sublimetext.com/sublimehq-pub.gpg"

GPG key url.


Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: webarchitect609.sublime_text }

License
-------

MIT

Author Information
------------------

This role was created in 2019 by Gripinskiy Sergey.
