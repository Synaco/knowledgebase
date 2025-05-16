# Inventory File

Ansible uses an inventory file to connect to the machines you will be
managing. You have to specify and create a group and then specify all
of the servers IP address's that will belong to that group like so:

> [group1]  
> 192.0.2.1

Once you have that set you can run the following command to make sure
it works:

```bash
ansible -i hosts.ini example -m ping -u [username]
```
