 Vagrant.configure("2") do |config|
config.vm.define "node1" do |node1|
  node1.vm.box = "bento/centos-6.7"
  node1.vm.network :private_network, ip: "192.168.56.22"
  node1.vm.hostname = "node1.mylab.local"
  config.vm.provision "shell", inline: <<-SHELL
    yum   update
    yum  install -y t
 echo "script ran"
 yum 
   SHELL
end
end