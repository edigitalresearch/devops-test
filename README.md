# Requirements

* git
* ansible
* vagrant


# Exercise
You will find a 'vagrant' and 'ansible' folder in this repository. The aim of  this exercise is to deploy apache (using ansible) to a virtual machine which is deployed using vagrant. To start, run `vagrant up` in the vagrant folder, check the Vagrantfile for any syntax errors and make sure the box has the IP address `192.168.33.10`.

When the vagrant box is up and running, you should then use ansible to deploy apache to it. You should install the required role using ansible-galaxy. Enjoy :)
