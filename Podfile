source 'https://github.com/CocoaPods/Specs'
source 'https://github.com/tuya/TuyaPublicSpecs.git'
source 'https://github.com/tuya/tuya-pod-specs.git'


target 'TuyaAppSDKSample-iOS-Swift' do
  use_modular_headers!

  pod 'SVProgressHUD'
  pod 'SGQRCode', '~> 4.1.0'

  pod 'ThingSmartHomeKit', '~> 5.1.0'

end

post_install do |installer|
  `cd TuyaAppSDKSample-iOS-Swift; [[ -f AppKey.swift ]] || cp AppKey.swift.default AppKey.swift;`
end
