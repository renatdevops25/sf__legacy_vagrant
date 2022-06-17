Так как в настоящий момент доступ к репозиторию Vagrant Cloud невозможен из России, добавил через <vagrant box add> свой образ в локальный репозиторий, поэтому мой Vagrantfile такой. Но если бы все работало как надо то он бы был следующего содерждания:
  
Vagrant.configure("2") do |config|
  config.vm.box = "renatdevops25/ub10-psql8-4"
  config.vm.box_version = "1.0.0"
end  
