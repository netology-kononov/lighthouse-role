lighthouse-role
=========

Role for Lighthouse installation.

Requirements
------------

No requirements.

Role Variables
--------------

accept variables:  
"lighthouse_vcs" - Git location of Lighthouse application, default value is: "https://github.com/VKCOM/lighthouse.git"  
"lighthouse_dir" - Application folder location, default value is: "/usr/share/lighthouse"  
"lighthouse_access_log" - Nginx access logs name, default value is: "lighthouse"  

Dependencies
------------

Git and Nginx applications should be installed on target host.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lighthouse-role

License
-------

MIT

Author Information
------------------

Created for learning purposes.
