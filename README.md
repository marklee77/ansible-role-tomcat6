marklee77.tomcat6
=======================

[![Build Status](https://travis-ci.org/marklee77/ansible-role-tomcat6.svg?branch=master)](https://travis-ci.org/marklee77/ansible-role-tomcat6)

tomcat6 role for Ubuntu.

Role Variables
--------------

- tomcat6_hostname: tomcat6 hostname. Set to "localhost" by default.
- tomcat6_server_port: tomcat6 server port. Set to 8005 by default.
- tomcat6_catalina_address: tomcat6 catalina bind address. Set to 127.0.0.1 by 
    default.
- tomcat6_catalina_port: tomcat6 catalina port. Set to 8983 by default.
- tomcat6_catalina_redirect_port: tomcat6 catalina redirect prot. Set to 8443 by 
    default.

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
