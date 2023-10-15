Role Name
=========

install and run watchtower container

Requirements
------------


Role Variables
--------------
| defaults variable | description |default value|mandatory|
|-------------------|-------------|-------------|---------|
|app_user|user for the install directory| pihole|no|
|docker_home|base install directory| /opt/docker|no|
|docker_dirs|installation sub-directory|watchtower|no|
|watchtower_env| template name| watchtower.env|no|
|timezone|Timezone| Europe/Vienna|no|
|smtp_port|smtp server port| 587|no|
|vault_smtp_server|smtp server|no default|yes|
|vault_smtp_login|smtp auth login|no default|yes|
|vault_smtp_password|smtp auth password|no default|yes|
|vault_mail_from_watchtower|from address|no default|yes|
|vault_mail_to_usr|to address|no default|yes|


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-watchtower }

License
-------

This project is licensed under the Attribution-NonCommercial-ShareAlike 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
