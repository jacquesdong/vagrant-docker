Vagrant.configure("2") do |config|
  config.vm.provider "docker" do |d|
    d.build_dir = "./build"
    d.remains_running = true
    d.has_ssh = true
  end

  config.vm.synced_folder ".", "/vagrant", disabled: true

  # config.vm.provision :shell, path: "bootstrap.sh", privileged: fals
end
