Run test commands on remote host

```bash
ansible azurehosts -m ping
ansible azurehosts -a "free -h"
```

run a playbook
```bash
ansible-playbook -i inventories/testing.yml playbooks/ping.yml
```
