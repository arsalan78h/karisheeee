
 platform :ios, '9.0'

target 'try collectionview' do
   
  use_frameworks!

  # Pods for try collectionview

post_install do |installer|
installer.pods_project.targets.each do |target|
target.build_configurations.each do |config|
config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
end
end
end
end
