Run test commands on remote host

```bash
ansible azurehosts -m ping
ansible azurehosts -a "free -h"
```

run a playbook
```bash
ansible-playbook -i inventories/testing.yml playbooks/ping.yml
```

run a playbook on a specific host
```bash
ansible-playbook -l pms18vm  playbooks/docker-install.yml
```
