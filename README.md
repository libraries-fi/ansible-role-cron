cron
========

Configures cron on a server. Very basic for now. Only for Debian and sets just
the logging level.

Role Variables
--------------

cron_logging_level: The logging level for cron. Defaults to full logging (15)
for now.

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - cron

License
-------

MIT
