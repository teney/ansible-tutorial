Vagrant.configure("2") do |config|
  config.vm.define :app01 do |app01|
    app01.vm.hostname = "app01"
    app01.vm.network :private_network, ip: '192.168.100.100'
    app01.vm.box = "centos/7"
  end
  config.vm.define :app02 do |app02|
    app02.vm.hostname = 'app02'
    app02.vm.network :private_network, ip: '192.168.200.200'
    app02.vm.box = "centos/7"
  end
  config.vm.define :lb01 do |lb01|
    lb01.vm.hostname = 'lb01'
    lb01.vm.network :private_network, ip: '192.168.250.250'
    lb01.vm.box = "bento/ubuntu-16.04"
  end
    config.vm.define :ms01 do |ms01|
    ms01.vm.hostname = 'myserver1'
    ms01.vm.network :private_network, ip: '192.168.10.10'
    ms01.vm.box = "bento/ubuntu-16.04"
  end
end