## quick commands

```
# Check if everything is ok
ansible nuage_pstack_controller -i openstack-hosts-inventory -m ping
ansible nuage_pstack -i openstack-hosts-inventory -m ping -e cluter_name=nuage_pstack

# Run playbook
ansible-playbook -i openstack-hosts-inventory -e cluster_name=nuage_pstack openstack_mitaka_create.yml

```
