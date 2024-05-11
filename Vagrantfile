# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
   config.vm.box = "ubuntu22.box"
   config.vm.box_check_update = false
   config.vm.hostname = "vm-ubuntu"
   config.vm.define "vm-ubuntu"
   config.vm.provider "virtualbox" do |vb|
     vb.memory = "2048"
   end
end
