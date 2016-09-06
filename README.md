# learning-ansible-vagrant
===

Vagrant repo for learning Ansible. Forked from Garrett Honeycutt's excellent work.

===

# Usage


`git clone https://github.com/gregdek/learning-ansible-vagrant`

`cd learning-ansible-vagrant`

`for ((i=1;i<=3;i++)); do vagrant up node$i; done && vagrant up admin`

`vagrant ssh admin`


### Example ansible command

`sudo ansible all -m ping`
