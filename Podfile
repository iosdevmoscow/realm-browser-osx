source 'git@github.com:realm/cocoapods-specs-private.git'
source 'https://github.com/CocoaPods/Specs.git'

platform :osx, '10.9'

use_frameworks!
workspace 'RealmBrowser.xcworkspace'

target 'RealmBrowser' do
    pod 'AppSandboxFileAccess'
    pod 'Realm', '1.0.1-1-sync-0.24.1'
    pod 'RealmConverter'
end

target 'RealmSyncServer' do
    project 'RealmSyncServer/RealmSyncServer.xcodeproj'
    pod 'LibRealmSyncServer', '0.24.1'
end
