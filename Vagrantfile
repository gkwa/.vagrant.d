# https://blog.talkingtotheduck.ca/how-to/2015/12/13/vagrant-cachier-with-test-kitchen/#global-vagrantfile-configuration
Vagrant.configure('2') do |config|
  if Vagrant.has_plugin?('vagrant-cachier')
    config.cache.scope = :box
  end
end
