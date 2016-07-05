VAGRANTFILE_API_VERSION = "2"


Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.provision :shell, :path => "bootstrap.sh"

  config.vm.network :forwarded_port, host: 8085, guest: 8080
  config.vm.network :forwarded_port, host: 8890, guest: 8888
end