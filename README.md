[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-maui.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-maui)

Maui Role
=======================

Install [Maui](http://www.adaptivecomputing.com/products/open-source/maui).  
Bear in mind that this role is to be used in combination with the grycap.torque role.

Example Playbook
----------------
```
- hosts: localhost
  roles:
  - { role: 'grycap.maui' }
```
Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
