# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.define "node1" do |node1|
    node1.vm.hostname = "node1"
    node1.vm.box = "bento/centos-7.3"
  end

  config.vm.define "node2" do |node2|
    node2.vm.hostname = "node2"
    node2.vm.box = "bento/ubuntu-16.04"
  end
end
