# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.ssh.insert_key = false
  config.vm.box = "gmoisio/vQFX-re"
  config.vm.box_version = "18.4"
  config.vm.define "vqfx01" do |vqfx01|
    vqfx01.vm.synced_folder ".", "/vagrant", disabled: true
    vqfx01.vm.host_name = "vqfx01"
    vqfx01.vm.boot_timeout = 600
  end

end
