# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'
source 'https://github.com/yusufhnf/DolanDolen-CorePodSpecs'
use_frameworks!

workspace 'Modularization'
target 'dolandolen' do
  pod 'Toast-Swift', '~> 5.0.1'
  pod 'Kingfisher', '~> 7.0'
  pod 'Alamofire', '~> 5.4'
  pod 'RxSwift', '6.2.0'
  pod 'RxCocoa', '6.2.0'
  pod 'SwiftLint'
  
  target 'Game' do
    project '../Game/Game'
  end
  
  target 'GameFavourite' do
    project '../GameFavourite/GameFavourite'
  end
  
  pod 'Core'
  
  target 'Common' do
    project '../Common/Common'
  end
  
  target 'dolandolenTests' do
    inherit! :search_paths
    # Pods for testing
  end
  
  target 'dolandolenUITests' do
    # Pods for testing
  end
end
