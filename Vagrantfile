
# -*- mode: ruby -*-

# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # Ubuntu 22.04 LTS
  config.vm.box = "ubuntu/jammy64"
  
  # Désactiver le dossier partagé (contournement pour WSL)
  config.vm.synced_folder ".", "/vagrant", disabled: true
  
  # Réseau privé avec IP fixe
  config.vm.network "private_network", ip: "192.168.56.100"
  
  # Ressources allouées
  config.vm.provider "virtualbox" do |vb|
    vb.name = "VM-Ubuntu-Andre"
    vb.memory = "1024"
    vb.cpus = 1
  end
end


# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # Ubuntu 22.04 LTS
  config.vm.box = "ubuntu/jammy64"
  
  # Désactiver le dossier partagé (contournement pour WSL)
  config.vm.synced_folder ".", "/vagrant", disabled: true
  
  # Forcer l'utilisation du mot de passe pour SSH
  config.ssh.password = "vagrant"
  config.ssh.insert_key = false
  
  # Réseau privé avec IP fixe
  config.vm.network "private_network", ip: "192.168.56.100"
  
  # Ressources allouées
  config.vm.provider "virtualbox" do |vb|
    vb.name = "VM-Ubuntu-Andre"
    vb.memory = "1024"
    vb.cpus = 1
  end
end


# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # Ubuntu 22.04 LTS
  config.vm.box = "ubuntu/jammy64"
  
  # Réseau privé avec IP fixe
  config.vm.network "private_network", ip: "192.168.56.100"
  
  # Ressources allouées
  config.vm.provider "virtualbox" do |vb|
    vb.name = "VM-Ubuntu-Andre"
    vb.memory = "1024"
    vb.cpus = 1
  end
end
