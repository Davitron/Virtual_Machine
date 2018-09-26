Vagrant.configure("2") do |config|
  config.vm.box = "Microsoft/EdgeOnWindows10"
  config.ssh.username = "IEUser"
  config.ssh.password = "Passw0rd!"

  config.vm.network "forwarded_port", host: 33389, guest: 3389, id: "udp", auto_correct: true
end
