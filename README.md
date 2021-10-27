Set Server Timezone
=========

This role can be used to set the Server Timezone.
![Build Status](https://github.com/Rheinwerk/ansible-role-set_server_timezone/actions/workflows/ci.yml/badge.svg)


Requirements
------------

None.


Role Variables
--------------

There is one main variable that drives this role: `_set_server_timezone`. It is a map that contains all configuration and settings for this role.
Please see `defaults/main.yml` for details.

Dependencies
------------

None.


Example Playbook
----------------

The general contract of this role is to take the variables map `_set_server_timezone` from `defaults/main.yml` as a template for your configuration and pass that configuration as a parameter to this role.

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      var:
        SET_SERVER_TIMEZONE
          ...
      roles:
         - { role: set_server_timezone, tags: [ 'set_server_timezone' ], _set_server_timezone: "{{ set_server_timezone }}" }

License
-------

Please see LICENSE.

Author Information
------------------

Original author is [Daniel Schneller](https://github.com/dschneller) as member of the [Rheinwerk](https://github.com/Rheinwerk) project.
