# -*- mode: ruby -*-
# vi: set ft=ruby :


Vagrant.configure("2") do |config|
  
  config.vm.box = "bento/centos-6.7"
  
  config.omnibus.chef_version = "12.10.24"
  
  config.vbguest.auto_update = false
  
  # config.vm.box_check_update = false

  
  # config.vm.network "forwarded_port", guest: 80, host: 8080

 
  # config.vm.network "forwarded_port", guest: 80, host: 8080, host_ip: "127.0.0.1"

  
   config.vm.network "private_network", ip: "192.168.33.30"

  
  # config.vm.network "public_network"

  
   config.vm.synced_folder "./", "/vagrant_data"

 
  # config.vm.provider "virtualbox" do |vb|
  #   # Display the VirtualBox GUI when booting the machine
  #   vb.gui = true
  #
  #   # Customize the amount of memory on the VM:
  #   vb.memory = "1024"
  # end


#   config.vm.provision "shell", inline: <<-SHELL
#     	sudo yum update
#	sudo yum install -y php
#	sudo yum install -y php-fpm
#	sudo rpm -ivh http://nginx.org/packages/centos/6/noarch/RPMS/nginx-release-centos-6-0.el6.ngx.noarch.rpm
#        sudo yum install -y nginx
#	sudo service nginx start
#	sudo chkconfig nginx on	
#	sudo service iptables stop
#	sudo chkconfig iptables off
	   
#   SHELL
end
