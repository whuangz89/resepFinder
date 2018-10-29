# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

use_frameworks!
workspace 'ResepFinder'

def networkAndParsingPods
  pod 'Alamofire', '~> 4.7'
end

def generalPods
  pod 'TPKeyboardAvoiding', '1.2.9'
end

target 'ResepFinder' do
  project 'ResepFinder'
  pod 'Firebase'
  pod 'Firebase/Core'
  generalPods
  networkAndParsingPods
end


target 'RFProfileMenu' do
  project 'RFProfileMenu/RFProfileMenu'
  generalPods
  networkAndParsingPods
end
