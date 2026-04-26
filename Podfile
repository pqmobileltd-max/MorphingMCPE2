# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'MorphingMCPE' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!

  # Pods for MorphingMCPE
pod 'FirebaseAppCheck', '10.15.0'
  pod 'FirebaseFunctions', '10.15.0'
  pod 'FirebaseCore', '~> 10.15'
  
  pod 'MBProgressHUD'
  pod 'SwiftyJSON'
  pod 'SwiftyStoreKit'
  pod 'Kanna'
  pod 'Alamofire'
  pod 'AlamofireImage'
  pod 'SDWebImage'
  pod 'ZIPFoundation'
end
post_install do |installer|
  installer.pods_project.targets.each do |target|
    target.build_configurations.each do |config|
      config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '12.0'
#      config.build_settings['HEADER_SEARCH_PATHS'] = '$(inherited) $(SDKROOT)/usr/include/libxml2'
    end
  end
end
