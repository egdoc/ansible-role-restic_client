Ansible Role: restic_client
==================

[![CI](https://github.com/egdoc/ansible-role-restic_client/actions/workflows/ci.yml/badge.svg)](https://github.com/egdoc/ansible-role-restic_client/actions/workflows/ci.yml)

Ansible role to install restic on Linux

Requirements
-------------
Requires bzip2 to be installed on targets, when installing restic directly from github.

Role Variables
--------------
See role [argument_specs.yml](https://github.com/egdoc/ansible-role-restic_client/blob/master/meta/argument_specs.yml)


Dependencies
------------
None

Example Playbook
----------------

    - hosts: workstations
      tasks:
        - name: Install restic
          ansible.builtin.import_role:
            name: egdoc.restic_client

License
-------

GPLv2

Author Information
------------------
Created by Egidio Docile
