# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|

  config.vm.define "vm1" do |vm1|
    vm1.vm.box = "centos/7"

    vm1.vm.provider :virtualbox do |v|
      v.memory = 2048
    end
  end
  
  config.vm.define "vm2" do |vm2|
    vm2.vm.box = "ubuntu/focal64"

    vm2.vm.provider :virtualbox do |v|
      v.memory = 2048
    end
  end
  
end
