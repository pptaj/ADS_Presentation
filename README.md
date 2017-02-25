# ADS_Presentation
#Introduction to vagrant
* Vagrant Commands
* Vagrant Installation
* Vagrant Advantages
* Difference between Vagrant and Docker

#Introduction to OpenStack
* OpenStack Information
* Installation
* TryStack

#Difference between Virtual Machine,Docker and Vagrant
* The short answer is that if you want to manage machines, you should use Vagrant. And if you want to build and run applications environments, you should use Docker 

Reference link: http://stackoverflow.com/questions/16647069/should-i-use-vagrant-or-docker-for-creating-an-isolated-environment

Reference link: https://www.quora.com/Whats-the-difference-between-a-VM-Docker-and-Vagrant

* Virtual Machine

![alt tag](https://qph.ec.quoracdn.net/main-qimg-c5288bd31cc118aaea15ee87310a331c-p)

* Docker 

![alt tag](https://qph.ec.quoracdn.net/main-qimg-ba6d33730d1bce36c28d6a04486b2574-p)

* Vagrant

![alt tag](https://qph.ec.quoracdn.net/main-qimg-7dd201f456a841238f1a469999245fc7-p)

#Difference between Vagrant & Docker
Reference Link: https://deliciousbrains.com/vagrant-docker-wordpress-development/
![alt tag](https://cdn.deliciousbrains.com/content/uploads/2016/01/07115244/VagrantVsDocker.jpg)


Reference Link: https://www.upguard.com/articles/docker-vs-vagrant
![alt tag](https://www.upguard.com/hs-fs/hubfs/UpGuard/infographics/docker-vs-vagrant.png?t=1487983775360&width=650&name=docker-vs-vagrant.png)


#Additional Information

# Creating Boxes in Vagrant
* Reference Link: https://scotch.io/tutorials/how-to-create-a-vagrant-base-box-from-an-existing-one
* You can run multiple Vagrant boxes concurrently, as long as their configuration does not clash with one another in some breaking way, e.g. mapping the same network ports on the host, or using same box names/IDs inside the same provider. There's no difference from having multiple boxes running on a provider manually, say multiple boxes on VirtualBox, or having them registered and started up by Vagrant. The result is the same, Vagrant just streamlines the process.

Reference Link: http://stackoverflow.com/questions/23888381/how-to-run-several-boxes-with-vagrant

# Vagrant vs Virtual Boxes
* Reference Link: https://www.quora.com/Why-should-I-use-Vagrant-instead-of-creating-multiple-VMs-in-VirtualBox-or-VMWare-Workstation

# Vagrant vs Virtual Boxes vs Ravello Smart Labs
* Reference Link: https://www.ravellosystems.com/blog/vargant-virtual-box/
