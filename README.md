# packer_boxes
This is a packer example that creates a box for virtual box.  
Enable to create minimal boxes for using this templates at once.

# Requirements
* ruby
* packer
   * http://www.packer.io/
* virtualbox
   * https://www.virtualbox.org/

# Output box
* Only virtualbox
   * CentOS-6.4-x86_64-minimal
   * ubuntu-12.04.3-server-amd64

# How To Use
```zsh
git clone https://github.com/mgi166/veewee_boxes.git
cd packer_boxes
packer build ./templates/CentOS-6.4-x86_64-minimal/virtualbox.json
```

This example output CentOS-6.4-x86_64-minimal.box.

# Caution

* ubuntu
   * For using vagrant, it is NECESSARY to using 'vagrant-vbguest' of vagrant plugin
* CentOS
   * For using vagrant, it is UNNECESARY to using 'vagrant-vbguest' of vagrant plugin

=====
