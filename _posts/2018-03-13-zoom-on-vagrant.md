---
layout: post
title: "Zoom on Vagrant"
date: 2018-03-13
tags : Zoomon Vagrant
---


Focus on Vagrant tool  
""Vagrant is a tool for building and managing virtual machine environments in a single workflow"""

## Root links

Vagrant Home : [https://www.vagrantup.com/](https://www.vagrantup.com/)

Vagrant documentation : [https://www.vagrantup.com/docs/](https://www.vagrantup.com/docs/)

Vagrant first steps : [https://www.vagrantup.com/intro/getting-started/](https://www.vagrantup.com/intro/getting-started/)

Vagrant sources : [https://github.com/hashicorp/vagrant](https://github.com/hashicorp/vagrant)

Vagrant cLI : [https://www.vagrantup.com/docs/cli/](https://www.vagrantup.com/docs/cli/)

CLI Cheatsheet 
* [https://gist.github.com/wpscholar/a49594e2e2b918f4d0c4](https://gist.github.com/wpscholar/a49594e2e2b918f4d0c4)
* [https://howtoprogram.xyz/2016/07/11/basic-vagrant-commands/](https://howtoprogram.xyz/2016/07/11/basic-vagrant-commands/)
* [https://www.cheatography.com/davbfr/cheat-sheets/vagrant-cheat-sheet/](https://www.cheatography.com/davbfr/cheat-sheets/vagrant-cheat-sheet/)

## Some vocab

Three important notions : 
* **Box:** A box is a packaged Vagrant environment, typically a virtual machine.
	* Boxes catalog : [https://app.vagrantup.com/boxes/search](https://app.vagrantup.com/boxes/search)
	* Boxes documentation : [https://www.vagrantup.com/docs/boxes.html](https://www.vagrantup.com/docs/boxes.html)
* **Provider:** A provider is the location in which the virtual environment runs. It can be local, remote or even a special case like a Docker container.
	* VirtualBox (default one) [https://www.virtualbox.org/](https://www.virtualbox.org/)
	* VMWare
	* Docker
	* Hyper-V
	* but you can also create your custom provider (ex AwS)
* **Provisioner:** A provisioner is a tool to set up the virtual environment, and can be as simple as a shell script, but alternatively a more advanced tool like Chef, Puppet, or Ansible can be used.


Everything is beginning with the Vagrant file (Ruby syntax [https://www.ruby-lang.org/fr/](https://www.ruby-lang.org/fr/))   

vagrantfile cheatsheet
* [https://gist.github.com/carlessanagustin/69d65ca1110c146598a9](https://gist.github.com/carlessanagustin/69d65ca1110c146598a9)
* [https://devhints.io/vagrantfile](https://devhints.io/vagrantfile)

## First steps

### Install

Requirements :   
* Install Vagrant
* Install provider you will use (can also be done through Vagrant plugin system)


```
$ vagrant init
A `Vagrantfile` has been placed in this directory. You are now
ready to `vagrant up` your first virtual environment! Please read
the comments in the Vagrantfile as well as documentation on
`vagrantup.com` for more information on using Vagrant.
```

A vagrant file have been created : myPath\Vagrantfile
Edit and replace base in config.vm.box = "base" with required boxe (public catalog [https://app.vagrantup.com/boxes/search](https://app.vagrantup.com/boxes/search))

Or you can initialize your vagrant file with required box

```
$ vagrant init debian/jessie64
A `Vagrantfile` has been placed in this directory. You are now
ready to `vagrant up` your first virtual environment! Please read
the comments in the Vagrantfile as well as documentation on
`vagrantup.com` for more information on using Vagrant.
```

Now ready for a vagrant up

```
$ vagrant up
Bringing machine 'default' up with 'virtualbox' provider...
==> default: Box 'debian/jessie64' could not be found. Attempting to find and install...
    default: Box Provider: virtualbox
    default: Box Version: >= 0
==> default: Loading metadata for box 'debian/jessie64'
    default: URL: [https://vagrantcloud.com/debian/jessie64](https://vagrantcloud.com/debian/jessie64)
==> default: Adding box 'debian/jessie64' (v8.10.0) for provider: virtualbox
    default: Downloading: [https://vagrantcloud.com/debian/boxes/jessie64/versions/8.10.0/providers/virtualbox.box](https://vagrantcloud.com/debian/boxes/jessie64/versions/8.10.0/providers/virtualbox.box)
    default:
==> default: Successfully added box 'debian/jessie64' (v8.10.0) for 'virtualbox'!
==> default: Importing base box 'debian/jessie64'...
==> default: Matching MAC address for NAT networking...
==> default: Checking if box 'debian/jessie64' is up to date...
==> default: Setting the name of the VM: SimpleVagrant_default_1520957127757_88163
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Running 'pre-boot' VM customizations...
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
    default:
    default: Vagrant insecure key detected. Vagrant will automatically replace
    default: this with a newly generated keypair for better security.
    default:
    default: Inserting generated public key within guest...
    default: Removing insecure key from the guest if it's present...
    default: Key inserted! Disconnecting and reconnecting using new SSH key...
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: No guest additions were detected on the base box for this VM! Guest
    default: additions are required for forwarded ports, shared folders, host only
    default: networking, and more. If SSH fails on this machine, please install
    default: the guest additions and repackage the box to continue.
    default:
    default: This is not an error message; everything may continue to work properly,
    default: in which case you may ignore this message.
==> default: Installing rsync to the VM...
==> default: Rsyncing folder: /cygdrive/c/DevSnoNov/DevWorking/ProjectSourcesGit/VagrantTry/SimpleVagrant/ => /vagrant

==> default: Machine 'default' has a post `vagrant up` message. This is a message
==> default: from the creator of the Vagrantfile, and not from Vagrant itself:
==> default:
==> default: Vanilla Debian box. See [https://app.vagrantup.com/debian](https://app.vagrantup.com/debian) for help and bug reports
```

Now connect to your VM

```
$ vagrant ssh

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
vagrant@jessie:~$
```

## Some Vagrant examples

Simple Vagrant with Java : [https://github.com/marcospereira/vagrant-java](https://github.com/marcospereira/vagrant-java)   


Vagrant Kafka example : [https://github.com/eucuepo/vagrant-kafka](https://github.com/eucuepo/vagrant-kafka)   
Vagrant Kafka another example : [https://github.com/imalik8088/vagrant-kafka-lab](https://github.com/imalik8088/vagrant-kafka-lab)   
Vagrant Kafka box : [https://app.vagrantup.com/fscm/boxes/kafka](https://app.vagrantup.com/fscm/boxes/kafka)    


Vagrant Ansible examples : [https://github.com/geerlingguy/ansible-vagrant-examples](https://github.com/geerlingguy/ansible-vagrant-examples)   
Vagrant Docker Java9 Windows : [https://technology.amis.nl/2017/10/11/quick-and-clean-start-with-java-9-running-docker-container-in-virtualbox-vm-on-windows-10-courtesy-of-vagrant/](https://technology.amis.nl/2017/10/11/quick-and-clean-start-with-java-9-running-docker-container-in-virtualbox-vm-on-windows-10-courtesy-of-vagrant/)   
Vagrant, Ansible, Clojure, PostgreSql : [https://medium.com/the-lazy-programmer/automating-your-dev-environment-setup-with-vagrant-and-ansible-c6790b3257a0](https://medium.com/the-lazy-programmer/automating-your-dev-environment-setup-with-vagrant-and-ansible-c6790b3257a0)    
Vagrant ElasticSearch : [https://github.com/mattjmcnaughton/virtual-elasticsearch-cluster](https://github.com/mattjmcnaughton/virtual-elasticsearch-cluster) and [https://mattjmcnaughton.com/post/creating-a-virtual-elasticsearch-cluster-with-ansible-and-vagrant/](https://mattjmcnaughton.com/post/creating-a-virtual-elasticsearch-cluster-with-ansible-and-vagrant/)       


Vagrant Hadoop ecosystem : [https://github.com/alexholmes/vagrant-hadoop-spark-hive](https://github.com/alexholmes/vagrant-hadoop-spark-hive)    
Vagrant Hadoop ecosystem : [https://github.com/martinprobson/vagrant-hadoop-hive-spark](https://github.com/martinprobson/vagrant-hadoop-hive-spark)    
Vagrant Hadoop ecosystem : [https://github.com/vangj/vagrant-hadoop-2.4.1-spark-1.0.1](https://github.com/vangj/vagrant-hadoop-2.4.1-spark-1.0.1)    
Vagrant Hadoop ecosystem : [https://github.com/bhawiyuga/hadoop-vagrant-config](https://github.com/bhawiyuga/hadoop-vagrant-config)    

## Some more resources

* [https://linuxacademy.com/howtoguides/posts/show/topic/22660-get-started-with-vagrant-get-the-vagrant-cheat-sheet](https://linuxacademy.com/howtoguides/posts/show/topic/22660-get-started-with-vagrant-get-the-vagrant-cheat-sheet)
* [https://linuxacademy.com/blog/linux/vagrant-cheat-sheet-get-started-with-vagrant/](https://linuxacademy.com/blog/linux/vagrant-cheat-sheet-get-started-with-vagrant/)
