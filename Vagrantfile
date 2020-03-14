Vagrant.configure("2") do |config|
  config.vm.box = "bento/centos-7.7"

  config.vm.define 'k8s-master' do |node|
    node.vm.provider "parallels" do |prl|
      prl.name = 'k8s-master'
      prl.update_guest_tools = true
  
      prl.memory = 2048
      prl.cpus = 2
    end
  end

  config.vm.define 'k8s-node1' do |node|
    node.vm.provider "parallels" do |prl|
      prl.name = 'k8s-node1'
      prl.update_guest_tools = true
  
      prl.memory = 2048
      prl.cpus = 2
    end
  end

  config.vm.define 'k8s-node2' do |node|
    node.vm.provider "parallels" do |prl|
      prl.name = 'k8s-node2'
      prl.update_guest_tools = true
  
      prl.memory = 2048
      prl.cpus = 2
    end
  end

  config.vm.define 'k8s-node3' do |node|
    node.vm.provider "parallels" do |prl|
      prl.name = 'k8s-node3'
      prl.update_guest_tools = true
  
      prl.memory = 2048
      prl.cpus = 2
    end
  end
end
