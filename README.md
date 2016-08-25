ansible-role-hosts
=========

Configures /etc/hosts via templating

Role Variables
--------------


`hosts`: list of {`address`, `name`} hashes as /etc/hosts entries

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: ansible-role-hosts
           hosts: 
             - address: '192.168.1.1'
               name: 'host1'
             - address: '192.168.1.2'
			   name: 'host2'

License
-------

MIT

