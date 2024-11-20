# Introduction

This set of demos and lab goes along with the: `Linux networking`.  You are welcome to run this code and I try to make it as self explanatory as possible.


# Vagrantfile

A Vagrantfile is provided that will create a Ubuntu 22.04 VM, and install the needed software on the VM.

This was tested using vagrant VirtualBox running on Windows 11.

```
vagrant up
```


Configure your ssh client with the following.  I use [MobaXterm](https://mobaxterm.mobatek.net/).
Hostname/IP address: 127.0.0.1
Port number: 2222
Username: vagrant
Private Key: <path/to/private_key>
Note: you’ll want x11 forwarding on

To get the location of the private key:

```
vagrant ssh-config
```


When you want to stop the VM, you can either run `vagrant suspend` to save the state so you can resume it later with `vagrant up`, or `vagrant halt` to shut the VM down.


#demos (demo1, demo2, demo3)

Module 1 provides an introduction to Linux networking -  the material provided will introduce the lab environment, some of the tools use (tshark, scapy), and do some preliminary configuration where a bridge is set up in Linux.

# Lab (lab1)

This is the material provided. A description of the lab and a script to run your solution and package up a submission are provided.

# License

For all files in this repo, we follow the MIT license.  See LICENSE file.
