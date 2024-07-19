
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.network "private_network", ip: "192.168.33.10"
  # config.vm.provision "shell", inline: "cat /vagrant/partido.txt"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "partido_playbook.yml"

  end
end
