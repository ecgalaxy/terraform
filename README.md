ECGALAXY terraform role
=======================

This Ansible role installs HashiCorp Terraform - https://www.terraform.io/

The following additional tools are also installed:

- `tflint`: performs the linting of the code.
- `tfsec`: performs static code analysis of Terraform files.

Requirements
------------

- The `unzip` command, which can be provided by `ecgalaxy.common_packages`.

Role Variables
--------------

See `vars` and `defaults` folders.

Dependencies
------------

- optional: ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.common_packages
        - ecgalaxy.terraform

License
-------

Copyright the European Union 2022.

Licensed under the EUPL-1.2 or later.

Author Information
------------------

ECGALAXY team.
