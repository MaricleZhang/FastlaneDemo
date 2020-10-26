source 'https://mirrors.tuna.tsinghua.edu.cn/git/CocoaPods/Specs.git'
#source 'https://github.com/CocoaPods/Specs.git'

platform:ios,'9.0'
inhibit_all_warnings!

workspace 'FastlaneDemo'
project 'FastlaneDemo.xcodeproj'

def ju_main
    pod 'AFNetworking', '4.0.0'
end

# target
targetNameArray = [
    "FastlaneDemo"
]

targetNameArray.each do |targetName|
    puts targetName + " Pod Installing..."
    
    target :"#{targetName}" do
        ju_main
    end
end

