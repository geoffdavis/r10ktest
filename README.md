r10ktest
--------

This is a test of the R10K Puppet module deployinator. It uses [Vagrant][vagrant] with the [vagrant-oscar][vagrant-oscar] plugin to deploy a test Master/Agent setup for experimentation.

Note that there is currently a bug with Oscar due to CentOS 6 having a default firewall in place. See [Github Issue 26][https://github.com/adrienthebo/oscar/issues/26] for details and a workaround.

Usage
-----

    vagrant plugin install oscar
    vagrant box add centosPupLabs http://puppet-vagrant-boxes.puppetlabs.com/centos-64-x64-vbox4210-nocm.box
	vagrant up

[vagrant]: http://vagrantup.com
[vagrant-oscar]: https://github.com/adrienthebo/oscar
