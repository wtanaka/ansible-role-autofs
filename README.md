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

### `autofs_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "autofs" is already in the
path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)


License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
