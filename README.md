# odoo-install

Set up a VM using ubuntu/trusty64 base box and provision it with odoo_install.sh to install odoo version 11.0

## Requires:

* Vagrant 1.9.1: https://www.vagrantup.com/downloads.html
* VirtualBox 5.1.28: https://www.virtualbox.org/wiki/Downloads


Clone the repository and then:

```
cd odoo-install
vagrant up
```

The Odoo instance will be accessible at http://192.168.33.12:8069/ (set in the Vagrantfile).




