Demo for Zabbix 7.0 HA proxy feature

```
ansible-playbook -i inventory/inv.yml create_vms.yml
ansible-playbook -i inventory/inv.yml deploy_zabbix.yml
ansible-playbook -i inventory/inv.yml monitoring.yml
```
