# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "bento/ubuntu-16.04"
  
  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get install -y ruby bundler
    cd /vagrant
    bundle install
  SHELL
end
