# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'TravelApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  pod 'Firebase/Core'
  pod 'Firebase/Auth'
  pod 'Firebase/Database'
  pod 'Firebase/RemoteConfig'
  pod 'RealmSwift'

end
post_install do |installer|
 installer.pods_project.targets.each do |target|
  target.build_configurations.each do |config|
   config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.2'
  end
 end
end