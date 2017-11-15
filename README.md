kubeadm-ansible
===============

ansible playbook to build kubernetes cluster

## requirements

* 1 master node and 1 or more minion node
* CentOS 7
* 2 GB or more of RAM per machine (any less will leave little room for your apps)
* 2 CPUs or more
* Unique hostname, MAC address, and product_uuid for every node
* ansible 2.4 or later

## usage

1. edit `hosts` file in this directory (write a master IP and minion IPs)
1. `$ ansible-playbook -i hosts -u root site.yml`
