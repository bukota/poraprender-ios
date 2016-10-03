source 'https://github.com/CocoaPods/Specs.git'
source 'https://bitbucket.org/privaliaiosrefactor/specs'
source 'https://github.com/Accengage/CocoaPodsSpecs.git'


# Uncomment this line to define a global platform for your project
platform :ios, '8.0'
# Uncomment this line if you're using Swift
use_frameworks!

#pods for the app
def used_pods
    pod 'RxSwift'
    pod 'RxCocoa'
    pod 'RxBlocking'
    pod 'Moya'
    pod 'Moya/RxSwift'
    pod 'AlamofireImage'
    pod 'ObjectMapper'
    pod 'CocoaLumberjack/Swift'
    pod 'Locksmith'
    pod 'UIColor_Hex_Swift'
    pod 'Localize-Swift'
    pod 'zipzap'
    pod 'Reachability', :git => 'https://github.com/ashfurrow/Reachability.git', :branch => 'frameworks'
    pod 'Moya-ObjectMapper/RxSwift'
    pod 'NSObject+Rx'
    pod 'MZFormSheetPresentationController'
    pod 'CollapsableTableKit'
    pod 'ImageSlideshow/Alamofire'
    pod 'FrameAccessor'
    pod 'BWSwipeRevealCell'
    pod 'DZNEmptyDataSet', :git => 'https://github.com/rcabamo/DZNEmptyDataSet'
    pod 'CryptoSwift'
    pod 'CarbonKit'
    pod 'Sheriff'
    pod 'SVProgressHUD', :git => 'https://github.com/msavula/SVProgressHUD'
    pod 'FloatLabelFields', :git => 'https://github.com/ferranabello/FloatLabelFields'
    pod 'IQKeyboardManagerSwift'
    pod 'XCDYouTubeKit'
end

def partners_pods
    pod 'NewRelicAgent', '5.5.1'
    pod 'Apptimize'
    pod 'FBSDKCoreKit'
    pod 'FBSDKShareKit'
    pod 'FBSDKLoginKit'
    pod 'Google/Analytics'
end

#publish to appstore target
target ‘PorAprender’ do
    used_pods
    partners_pods
end

#developing target NOT for publishing
target ‘PorAprender Development’ do
    used_pods
    partners_pods
end

#test target
target ‘PorAprenderTests' do
    used_pods
    pod 'Google/Analytics'
end
