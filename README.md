Basic Ansible playbook for Linode
======

Given a default install of Ubuntu on Linode this playbook does the following:

  * Sets the hostname
  * Sets the timezone
  * Creates a new user for ssh
  * Uploads a ssh public key for the above user
  * Creates a basic firewall
  * Disables ssh root login
  * Disables ssh password login

##Usage
```ansible-playbook linode_playbook.yml -i hosts --ask-pass```

##To improve
Ideally all the variables set should be configurable.
