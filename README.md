Drawio
=========

Downloads the latest Draw.io Desktop release from Github and installs it.

Dependencies
------------
community.general collection - install with `ansible-galaxy collection install community.general`
github3.py

Example Playbook
----------------

    - hosts: desktop
      roles:
         - drawio

License
-------

MIT