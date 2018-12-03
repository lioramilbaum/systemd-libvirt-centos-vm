Vagrant.configure(2) do |config|
  config.vm.box = "centos/7"
  config.vm.provider "libvirt" do |libvirt|
    libvirt.memory = 2048
    libvirt.cpus = 1
    libvirt.nested = true
    libvirt.volume_cache = 'none'
    libvirt.driver = "kvm"
    libvirt.uri = "qemu:///system"
    libvirt.connect_via_ssh = false
    libvirt.username = "root"
  end
end