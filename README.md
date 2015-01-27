Airtime
=========

[![Build Status](https://travis-ci.org/mathieumd/ansible-role-airtime.svg?branch=master)](https://travis-ci.org/mathieumd/ansible-role-airtime)

This Ansible role install [Airtime](https://www.sourcefabric.org/en/airtime/),
an "open source platform that lets you broadcast streaming radio on the web".

Role Variables
--------------

Default Airtime `admin` password is `MyPassword`, set in
[defaults](defaults/main.yml) through `airtime_pass_md5`. To generate your own
password, use the command `echo -n "MyPassword" | md5sum`.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-role-airtime

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl.html)

