Vagrant.configure("2") do |config|

config.vm.define "node1" do |node1|
  node1.vm.box = "bento/centos-7.2"
  node1.vm.network "private_network", ip: "192.168.33.10"
end

config.vm.define "node2" do |node2|
  node2.vm.box = "bento/centos-7.2"
  node2.vm.network "private_network", ip: "192.168.33.11"
end



  # config.vm.network "forwarded_port", guest: 80, host: 8080
  # config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1"
  # config.vm.synced_folder "../data", "/vagrant_data"
  # config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end
  #
  # config.vm.provision "shell", inline: <<-SHELL
  #   apt-get update
  #   apt-get install -y apache2
  # SHELL
end
