# Vagrant virtual box running ubuntu and lamp

[![Twitter](https://img.shields.io/twitter/url/https/github.com/cogitatio/vagrant-hostsupdater.svg?style=social)](https://twitter.com/intent/tweet?text=Checkout%20this%20Vagrant%20setup!&url=https%3A%2F%2Fgithub.com%2Fricdev%2Fvagrant-vm-ubuntu-lamp&hashtags=lamp,vagrant,vm,virtualmachine,virtualbox) [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/ricdev)

Lamp development environment using Vagrant VM. This is a documentation of what I'm using when developing php-based applications. 

## Machine Info
* vm name: vagrant.dev
* vm ip: 10.10.10.10
* vm host port: 5513
* vm port: 22

## Apache Info
* vhosts: awesome.dev, moreawesome.dev
* alias: <none>
* document root: /var/www/awesome
* directory block: /var/www/awesome
* port: 80

## mySQL
* root user: root
* root password: 123
* database user: dbuser
* root password: 123
* database: dbname

## References
* Vagrant cli commands: https://www.vagrantup.com/docs/cli/
* Config generator: https://www.puphpet.com/
* Foodshow Plugin: https://github.com/express42/vagrant-foodshow
* Foodshow + NGRok: https://cloudavail.com/2014/06/20/vagrant-from-internet/
* vagrant plugins: https://github.com/mitchellh/vagrant/wiki/Available-Vagrant-Plugins
* https://return-true.com/beginners-guide-using-vagrant-with-puphpet-for-local-development/
* https://www.sitepoint.com/build-virtual-machines-easily-puphpet/

## Notes
* use 'vagrant provision' when reloading puphpet configuration
* on terminal, 'ngrok http -host-header=rewrite targetvhost:80' to broadcast
