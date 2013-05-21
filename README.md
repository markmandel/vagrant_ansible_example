Example Vagrant + Ansible Project
----------------------------------------

Just me mucking around with Ansible and Vagrant.

Items installed:

- Java (thanks to [Webupd8 Java PPA](http://www.webupd8.org/2012/01/install-oracle-java-jdk-7-in-ubuntu-via.html))

This example does use [Roles](http://ansible.cc/docs/playbooks.html#roles), which are an Ansible 1.2 feature, and therefore
you will need to checkout Ansible from Git.

This also uses a [External Inventory Ansible plugin](http://ansible.cc/docs/api.html#external-inventory-scripts) to configure the IP of the Vagrant host.