Ansible Vim role
================

This Ansible role will install Vim and some plugins together with my Vim configuration.


Requirements
------------

None

Role Variables
--------------

`local_repositories_dir` specifies where to clone Git repositories. I like to have them all in one place and symlink them to where they are needed.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ROBERTLARSEN.vim }

License
-------

GPLv2

Author Information
------------------


