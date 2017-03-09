# vagrant-activemq
Provision a Vagrant Box with ActiveMQ

Assumes you have already installed VirtualBox and Vagrant.

## Run Instance
- Clone this Repo
- Run `vagrant up`

You can access the ActiveMQ Admin at `http://10.0.10.34:8161/admin`

## Connecting using a Java client
Java connections to this `ActiveMQ` instances can use this configuration:
user: admin
password: admin
url: tcp://10.0.10.34:61616