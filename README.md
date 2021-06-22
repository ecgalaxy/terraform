ECGALAXY terraform role
=======================

Installs HashiCorp Terraform - https://www.terraform.io/

Requirements
------------

None.

Role Variables
--------------

See `vars` folder.

Dependencies
------------

* ecgalaxy.bootstrap

Example Playbook
----------------

- hosts: all
  roles:
    - ecgalaxy.bootstrap
    - ecgalaxy.terraform

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
