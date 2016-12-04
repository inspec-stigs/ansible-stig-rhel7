# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.synced_folder ".", "/vagrant", type: "nfs"
  config.vm.network :private_network, ip: "172.16.0.100"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "site.yml"
    #ansible.tags = 'stig_rhel_07_010020'
    #ansible.verbose = true
    ansible.sudo = true
  end
end
