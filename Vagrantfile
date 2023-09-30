require 'config_builder'
Vagrant.configure('2', &ConfigBuilder.load(
  :yaml,
  :yamldir,
  File.expand_path('../config.vagrant', __FILE__)
))
