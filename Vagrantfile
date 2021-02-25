
#Création des serveurs :serveur Web et serveur de base de données


Vagrant.configure("2") do |configuration|

#serveur de bases de données
  configuration.vm.define "MachineDb" do |config|

    config.vm.box = "centos/7"
    config.vm.hostname = "machineDb"
    config.vm.network :private_network, ip: "192.168.33.200"
    config.vm.provider "virtualbox" do |vb|
		vb.memory = "3096"
	end
    end


#serveur Web
  configuration.vm.define "MachineWeb" do |config|
    
    config.vm.box = "centos/7"
    config.vm.hostname = "machineWeb"
    config.vm.network :private_network, ip: "192.168.33.250"
    config.vm.provider "virtualbox" do |vb|
		vb.memory = "3096"
	end 
    end


end
