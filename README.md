ansible-role-oletools
=========

Ansible Role to install the DidierStevensSuite. These set of tools are helpful in analyzing malicious or suspicious documents like docx, xlsx, pdf, eml, and so on.

Requirements
------------

- Debian based OS like Ubuntu.

Role Variables
--------------

- destination_folder: The tools are cloned in `HOME_DIRECTORY/tools/dd-suite`
- packages: Pre-requisites required for installation of DidierStevensSuite
- pip_packages: Python packages required to run tools in DidierStevensSuite
- repo: Repo URL for DidierStevensSuite
- role_tags: There's a default tag named `oletools`. You can add more if required.

Dependencies
------------

- No other dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - ansible-role-oletools

License
-------

BSD

Author Information
------------------

- Author: Sudhir Shirsath
