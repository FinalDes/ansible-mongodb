MongoDB Setup
=========

[![Build Status](https://travis-ci.org/FinalDes/ansible-mongodb.svg?branch=master)](https://travis-ci.org/FinalDes/ansible-mongodb)

Basic MongoDB Setup

Requirements
---

Please look official document ubuntu and debian version support before run the task. This role will not check if the ubuntu and debian OS host is support or not.

Role Variables
--------------

**version:** mongodb version support `4.0, 3.6, 3.4, 3.2, 3.0`  
**port:** mongodbdb port default `27017`  
**bindIp:** mongodb access IP Address default `127.0.0.1`  
**dbPath:** mongodb storage path default `/var/lib/mongodb`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

``` YAML
    - hosts: servers
      roles:
         - { role: mongdb, version: 3.4 }
```

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
