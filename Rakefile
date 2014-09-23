# -*- coding: utf-8 -*-
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'
require 'bubble-wrap/core'



begin
  require 'bundler'
  Bundler.require
rescue LoadError
end

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'smartsc'
  app.device_family = :ipad
  app.deployment_target = '6.0'
  app.codesign_certificate = 'iPhone Developer: Dong Wang (7Y59E87GCZ)'
  app.identifier = 'de.i2dm.smartsc'


end
