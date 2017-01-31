ansible-package_update
======================

[![Build Status](https://travis-ci.org/galexrt/ansible-package_update.svg?branch=master)](https://travis-ci.org/galexrt/ansible-package_update)

A simple Ansible role to update your system. It updates all your packages on the system using the installed package manager.

Requirements
------------

No requirements.

Role Variables
--------------

```
# Used for apt updates
package_update_upgrade_mode: "safe"
```

Dependencies
------------

No dependencies.

Example Playbook
----------------

An example playbook on how to use this role:

    - hosts: servers
      roles:
         - { role: galexrt.package_update, package_update_upgrade_mode: "safe" }

License
-------

MIT

Author Information
------------------

If you have problems with the role, feel free to create an issue on Github or contact me by mail.
