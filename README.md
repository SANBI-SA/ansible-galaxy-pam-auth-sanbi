# ansible-galaxy-pam-auth-sanbi
Install PAM auth configuration for Galaxy (SANBI setup)

This role depends on variables that are used by the galaxyproject/ansible-galaxy role.

It installs auth_conf.xml to the Galaxy config/ directory and installs the python-pam module to Galaxy's virtualenv
and the pam.d configuration as used at SANBI.
