Ansible Role ModPageSpeed
=========

[![Build Status](https://travis-ci.com/cloudweeb/cloudweeb.mod_pagespeed.svg?branch=master)](https://travis-ci.com/cloudweeb/cloudweeb.mod_pagespeed)

Ansible role to install mod_pagespeed on apache web server

Requirements
------------

None

Role Variables
--------------

A description of the settable variables for this role should go here, including
any variables that are in defaults/main.yml, vars/main.yml, and any variables
that can/should be set via parameters to the role. Any variables that are read
from other roles and/or the global scope (ie. hostvars, group vars, etc.) should
be mentioned here as well.

Dependencies
------------

geerlingguy.apache

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - geerlingguy.apache
         - cloudweeb.mod_pagespeed

License
-------

MIT / BSD

Author Information
------------------

Agnesius Santo Naibaho
