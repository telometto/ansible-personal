Role Name
=========

Role to get up and running on my desktop from a fresh Fedora install.

Requirements
------------

The only requirement is that the 'Community General' module is installed from Ansible Galaxy. To install it, you need to run: `ansible-galaxy collection install community.general`.

Role Variables
--------------

The script is meant to be modular. Nothing is set under `defaults/main.yml` but the `vars/` dir contains a lot of files withvariables which are supposed to be set according to your
needs, such as packages, repos, URLs etc. You can nuke and pave anything under the `vars/` dir without having to touch the rest of the script, but that's entirely up to you.

Dependencies
------------

See 'Requirements'

Example Playbook
----------------

Just run `ansible-playbook -K site.yml` from inside the `playbooks/` dir, and you're good to go.

License
-------

GNU AFFERO GENERAL PUBLIC LICENSE

Author Information
------------------

telometto
