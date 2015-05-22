# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  # All Vagrant configuration is done here. The most common configuration
  # options are documented and commented below. For a complete reference,
  # please see the online documentation at vagrantup.com.

  # Every Vagrant virtual environment requires a box to build off of.
  config.vm.box = "boxcutter/ubuntu1504"
  
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "main.yml"
  end

  config.vm.network :forwarded_port, host: 8081, guest: 80
  config.vm.network :forwarded_port, host: 8080, guest: 443
  config.vm.network :forwarded_port, host: 8000, guest: 8000
  config.vm.network :forwarded_port, host: 8001, guest: 8001
  config.vm.network :forwarded_port, host: 8010, guest: 8010
  config.vm.network :forwarded_port, host: 8011, guest: 8011
  config.vm.network :forwarded_port, host: 8012, guest: 8012
  config.vm.network :forwarded_port, host: 8020, guest: 8020
  config.vm.network :forwarded_port, host: 8030, guest: 8030
  config.vm.network :forwarded_port, host: 8112, guest: 8112
  config.vm.network :forwarded_port, host: 8181, guest: 8181
  config.vm.network :forwarded_port, host: 8888, guest: 8888
  config.vm.network :forwarded_port, host: 8989, guest: 8989
  config.vm.network :forwarded_port, host: 9091, guest: 9091
  config.vm.network :forwarded_port, host: 32400, guest: 32400

  
end
