[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/grycap/ansible-role-maui.svg?branch=master)](https://travis-ci.org/grycap/ansible-role-maui)

Maui Role (DEPRECATED)
=======================

Install [Maui](http://www.adaptivecomputing.com/products/open-source/maui).  
Bear in mind that this role is to be used in combination with the grycap.torque role.

Warning: Adaptative computing is no longer supporting Maui. Instead, they recommend to use MOAB (http://www.adaptivecomputing.com/products/maui/)

Role Variables
----------------

The variables that can be passed to this role and a brief description about them are as follows.

	# MAUI version to install
	maui_version: 3.3.1

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
