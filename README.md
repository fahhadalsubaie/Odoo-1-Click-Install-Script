# Odoo 1-Click Install Script

A bash shell script to auto install odoo with ease.

All you have to do is to follow below instruction on a fresh ubuntu server version 16.04, 18.04, 20.04 and 22.04 (could be used for other version too but not tested).

This script will install Odoo on your Ubuntu server. It can install multiple Odoo instances in one server because of the different xmlrpc_ports.

# Installation method:

Using a root user or a user in the sudo group:

```
sudo nano odoo-install.sh
```

Paste the `odoo-install.sh` file content inside it, and edit the configuration part of the script as per your needs then hit `ctrl+x` to save then `y` to confirm then hit `enter`.

make the file executable by excuting the following command:

```
sudo chmod +x odoo-install.sh
```

Execute the script to install Odoo:

```
./odoo-install.sh
```

And that's it, you have your odoo 16 instance up and running!
