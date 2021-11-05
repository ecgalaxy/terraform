ECGALAXY terraform role
=======================

The role installs HashiCorp Terraform - https://www.terraform.io/
The following additional tools are also installed:
- `tflint`: performs the linting of the code.
- `tfsec`: performs static code analysis of terraform files.

Requirements
------------

None.

Role Variables
--------------

See `vars` and `defaults` folders.

Dependencies
------------

- ecgalaxy.common_packages

Example Playbook
----------------

    - hosts: all
      roles:
        - ecgalaxy.common_packages
        - ecgalaxy.terraform

License
-------

EUPL-1.2

Author Information
------------------

ECGALAXY team.
