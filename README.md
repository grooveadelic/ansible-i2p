# I2P

This is a fork of the deprecated role [grooveadelic/ansible-i2p](https://github.com/grooveadelic/ansible-i2p)

Ansible role to provision a linux system with I2P ([geti2p.net](https://get2ip.net) - Invisible Internet Project)


Role Variables
--------------

User for I2P installation and runtime.
`i2p_user: i2p`


Example Playbook
----------------

    - hosts: i2p.nodes
      roles:
        - sleepy_nols.ansible-i2p



License
-------

GPLv3

## Contribute

Bug reports, flag/toggle proposals and patches welcome.
