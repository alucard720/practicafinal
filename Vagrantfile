
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/jammy64"
  config.vm.network "private_network", type: "dhcp"
  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "partido_playbook.yml"

  end
end
