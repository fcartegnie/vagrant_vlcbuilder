
Requires [Vagrant](http://downloads.vagrantup.com/) and [Virtualbox](https://www.virtualbox.org/) on your system.

Usage 
===========

Creates Win32 build environment on 64 bits Debian.
Uses puppet for provisioning.

    git clone --recursive https://github.com/fcartegnie/vagrant\_vlcbuilder.git

Change to that directory and make your changes to Vagrantfile.

    vagrant up

At the end of the provisioning process, a configured build environment should be available in:

    /home/vagrant/vlc/win32/

after login into the VM with

    vagrant ssh

For more info, consult the [Vagrant Website](http://www.vagrantup.com/)

