Role Name: AzureJenkins
=========

[![Build Status](https://travis-ci.org/hemanth22/ansible-role-azurejenkins.svg?branch=master)](https://travis-ci.org/hemanth22/ansible-role-azurejenkins)

This role creates azure vm and install jenkins.

Requirements
------------

You need to install python-pip and boto to launch this EC2 based ansible module.

Role Variables
--------------

Try exploring defaults/main.yml in the github to understand which variables can be override.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - { role: hemanth22.azurejenkins }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2020 by Hemanth BITRA
