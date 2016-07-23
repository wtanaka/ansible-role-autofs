[![Build Status](https://travis-ci.org/wtanaka/ansible-role-autofs.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-autofs)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-autofs.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-autofs)

wtanaka.autofs
==============

Install autofs

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: wtanaka.autofs, autofs_net_state: present }

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
