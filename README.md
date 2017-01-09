bookedscheduler
=========

Installs Booked Scheduler (https://www.bookedscheduler.com) source code and templates configuration files. The source code can be retrieved from a local archive file, a local directory, or a Git repository. The latter two are useful if you want to make custom modifications to the source code.

Requirements
------------

Apache, MySQL and PHP (see Dependencies).

Role Variables
--------------

See defaults/main.yml.

Dependencies
------------
This role has been tested with the following:
- geerlingguy.apache (version: 1.7.3)
- geerlingguy.mysql (version: 2.4.0)
- geerlingguy.php (version: 3.3.0)
- jdauphant.ssl-certs (version: 1.2.5)



Example Playbook
----------------

An example of how to use this role can be found in https://github.com/hajaalin/bookedscheduler-deploy-example.

License
-------

GPLv3

Author Information
------------------

Harri Jäälinoja
