Role Name
=========

Installs Booked Scheduler source code and templates configuration files. The source code can be retrieved from a local archive file (default is the official Booked distribution), a local directory, or a Git repository. The latter two are useful if you want to make custom modifications to the source code.

Requirements
------------

Apache, MySQL and PHP (see Dependencies).

Role Variables
--------------

See defaults/main.yml.

Dependencies
------------
This role has been tested with the following:
- geerlingguy.apache (version: 1.5.3)
- geerlingguy.mysql (version: 1.9.1)
- geerlingguy.php (version: 1.8.2)



Example Playbook
----------------

An example of how to use this role can be found in https://github.com/UH-LMU/bookedscheduler-deploy.

License
-------

BSD

Author Information
------------------

Harri Jäälinoja.
