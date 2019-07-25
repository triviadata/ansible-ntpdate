ntpdate
=========

[![Build Status](https://travis-ci.com/triviadata/ansible-ntpdate.svg?branch=master)](https://travis-ci.com/triviadata/ansible-ntpdate)

Synchronize Linux host via ntpdate.

Requirements
------------
None.

Role Variables
--------------
Variables are listed in `defaults/main.yml` and desribed below:

* **ntpdate_server**: NTP Server used for synchronization

Dependencies
------------
None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: triviadata.ntpdate

License
-------

BSD

Author Information
------------------
This role was created in July 2019 by Matus Cuper
