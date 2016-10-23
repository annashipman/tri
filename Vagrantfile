# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

   config.vm.provision "shell", inline: <<-SHELL
     sudo apt-get update
     sudo apt-get install -y apache2
   SHELL

  # Intall go 1.7
  # Follow slides to install cobra
  # Need to set GOBIN "/usr/local/go" and GOPATH="/home/vagrant/go"
  # Can check this with goenv

  # All code should be in /home/vagrant/go/src/github.com/annashipman/tri but isn't apparently

  #
end
