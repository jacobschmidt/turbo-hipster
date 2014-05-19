Vagrant::Config.run do |config|

  config.vm.box = "precise32"
  config.vm.box_url = "http://files.vagrantup.com/precise32.box"
  config.vm.forward_port 4000, 4000
  config.vm.provision :shell,
    :inline => "sudo apt-get update && sudo apt-get -y install build-essential git ruby1.9.3 && sudo gem install jekyll --no-ri --no-rdoc && sudo gem install therubyracer"

  config.ssh.forward_agent = true
end