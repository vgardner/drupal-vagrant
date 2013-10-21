Drupal Vagrant
==============

A project template for quickly building local Drupal 8 compatible development environments.

### Requirements

* [VirtualBox](http://www.virtualbox.org/)
* [Vagrant](http://www.vagrantup.com/)

### Basic Usage

1. Clone this repo into a local folder:

        host$ git clone git://github.com/vgardner/drupal-vagrant.git
        host$ cd drupal-vagrant

2. Download a copy of Drupal into drupal-vagrant/dev

3. Configure settings file - default db settings are:

        Username: root
        Password: root
        Db name: drupal
        
4. Add VM to hosts file:

        192.168.56.101 drupal.dev
        
6. Access your VM via drupal.dev:8080 

7. You can log into the VM via: 
        host$ vagrant up
        host$ vagrant ssh


