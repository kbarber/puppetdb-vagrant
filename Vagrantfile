# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.provider "vmware_fusion" do |v|
    v.vmx["memsize"] = "2048"
    v.vmx["numvcpus"] = "2"
  end

  config.vm.define "centos-5.10-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/centos-5.10-64-nocm"
  end
  config.vm.define "centos-6.5-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/centos-6.5-64-nocm"
  end
  config.vm.define "debian-7.4-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/debian-7.4-64-nocm"
  end
  config.vm.define "ubuntu-12.04-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/ubuntu-12.04-64-nocm"
  end
  config.vm.define "ubuntu-13.04-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/ubuntu-13.04-64-nocm"
  end
  config.vm.define "ubuntu-13.10-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/ubuntu-13.10-64-nocm"
  end
  config.vm.define "ubuntu-14.04-64-nocm" do |vm|
    vm.vm.box = "puppetlabs/ubuntu-14.04-64-nocm"
  end
end
