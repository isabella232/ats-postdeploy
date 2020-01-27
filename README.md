# Post-deployment tasks for Eucalyptus Clouds

Edit 'hosts' file to put cloud's head-node IP:

```
vi hosts
```

Run the playbook:

```
ansible-playbook -i hosts playbook.yml --extra-vars 'ats_demo_state=present'
```