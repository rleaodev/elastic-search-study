Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/focal64"

  config.vm.define "elasticsearch" do |es7|
    es7.vm.network "private_network", ip: "192.168.56.30"
    
    es7.vm.provider "virtualbox" do |v|
      v.memory = 4096
      v.cpus = 2
    end
  end
end
