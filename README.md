# rcj-infrastructure
Ansible configuration to setup a fully-featured RCJ web server.

This includes basic CentOS configuration, a database (MariaDB), the RCJ soccer platform and the RCJ app server (todo).

To run, edit the *inventory* file with your server hostname or IP, then run:

```bash

ansible-playbook -i inventory site.yml
```

Then follow the prompts to enter configuration details.
