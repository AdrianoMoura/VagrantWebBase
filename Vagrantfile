# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "MyBox"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "MyBox"
  config.vm.synced_folder ".", "/var/www", owner: "www-data"

end