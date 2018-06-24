# I2P

A brief description of the role goes here.

Requirements
------------

 - java - in order to run I2P
 - pip - for installing pexpect, which is used for the interactive I2P installer

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Example Playbook
----------------

    - hosts: i2p.nodes
      pre_tasks:
        - user: name=i2p createhome=yes state=present
      roles:
        - geerlingguy.java 
        - geerlingguy.pip

        - role: grooveadelic.i2p
          i2p_user: i2p
          i2p_install_path: /home/i2p/i2p
          i2p_version: 0.9.34
          i2p_sha256sum: 61a255911dbe6a3196ddae9c445ffa543c321320f98f48dc880d6f0e0cc0a259

License
-------

GPLv3

Author Information
------------------

Tips/donations welcome ltc1qudlkn0kmca4xhypz4wmkxhtzmwgm80sl93larn
