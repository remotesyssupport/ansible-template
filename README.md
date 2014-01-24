Ansible 
=======


Directory Structure
===================
<pre>
--- ansible-cfg			
--- files			
--- handlers			
--- inventory			
------- hosts			
----------- group_vars			
----------- host_vars			
----------- localhost			
--- playbooks						
------- add-ssh-key.yml
--- plugins
------- action
------- callback
------- connection
------- filter
------- inventory
------- library
------- lookup
------- vars
--- roles
------- apt_sources
----------- defaults
--------------- main.yml
----------- handlers
--------------- main.yml
----------- meta
--------------- main.yml
----------- tasks
--------------- main.yml
----------- templates
--------------- sources-list.j2
----------- vars
--------------- main.yml
--- scripts
--- secrets
--- templates
</pre>
