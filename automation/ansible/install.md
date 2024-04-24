# Ansible Installation Guide


## Installing pip

You need `pip` to install ansible in order to upgrade ansible using the
command:

```bash
pip install --upgrade ansible
```

To install `pip` on Ubuntu run the following command:

```bash
sudo apt install pip
```

You will need to add the following locations to your PATH:

* /home/$USER/.local/bin
* /home/$USER/.local/bin 

The first location is for the ansible, ansible-config, 
ansible-connection, ansible-console, ansible-doc, ansible-galaxy, 
ansible-inventory, ansible-playbook, ansible-pull and ansible-vault
scripts. The second location is for the ansible-community script.

You can run the following command to make sure anisble is installed
and working properly:

```bash
ansible --version
```

