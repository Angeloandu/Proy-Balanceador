Vagrant.configure("2") do |config|
  config.vm.define "balanceador" do |balanceador|
    balanceador.vm.box = "bento/ubuntu-22.04"
    balanceador.vm.network "private_network", ip: "192.168.50.10"
    balanceador.vm.hostname = "balanceador"
  end
  config.vm.define "web1" do |web1|
    web1.vm.box = "bento/ubuntu-22.04"
    web1.vm.network "private_network", ip: "192.168.50.11"
    web1.vm.hostname = "web1"
  end
  config.vm.define "web2" do |web2|
    web2.vm.box = "bento/ubuntu-22.04"
    web2.vm.network "private_network", ip: "192.168.50.12"
    web2.vm.hostname = "web2"
  end
end