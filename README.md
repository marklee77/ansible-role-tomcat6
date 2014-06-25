marklee77.tomcat6
=======================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-tomcat6.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-tomcat6)

tomcat6 role for Ubuntu.

Role Variables
--------------

- tomcat6_hostname: localhost
- tomcat6_http_port: 8000

Example Playbook
-------------------------

    - hosts: all
      sudo: True
      roles:
        - marklee77.tomcat6

License
-------

GPLv2

Author Information
------------------

http://marklee77.github.io/
