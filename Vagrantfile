Vagrant.configure("2") do |config|
  ENV['VAGRANT_DEFAULT_PROVIDER'] = 'docker'
  config.vm.provider "docker" do |d|
    d.image = "monkeyswithbuttons/debian-jessie"
    d.has_ssh = true
  end
end
