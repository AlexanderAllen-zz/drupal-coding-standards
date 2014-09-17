Drupal Coding Standards
=============

Installs Drupal Coding Standards for Code Sniffer (PHPCS).

Requirements
------------

- PHP
- Composer
- PHP Code Sniffer

Role Variables
--------------

The coding standards in this playbook are meant to be used with PHP Code Sniffer.
This playbook assumes that Code Sniffer has been already installed.
The directory where Composer downloads packages to can be specified in `vars/main.yml`:

    dcs_comp_user_dir: /home/vagrant/.composer

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: webservers
      roles:
         - { role: AlexanderAllen.Liara }

Inside `vars/main.yml`:

    # Directory where Composer packages are installed to.
    dcs_comp_user_dir: /home/vagrant/.composer

License
-------

GPLv2

Author Information
------------------

https://github.com/AlexanderAllen
