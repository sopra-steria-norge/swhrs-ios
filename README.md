Using the code from https://github.com/steria/swhrs-app, puts it to the www-folder for Phonegap.

Be ware that _ALL_ websites are enabled, by adding *.* to ExternalHosts in Resources/Cordova.plist
The app will however not work before a working server address is added to www/js/global-variables.js

Had some problems with pushing the app to device, but got help from the following links:
http://docs.phonegap.com/en/2.1.0/guide_getting-started_ios_index.md.html#Getting%20Started%20with%20iOS
http://zsprawl.com/iOS/2012/10/installing-cordovaphonegap-2-1-for-ios/
http://stackoverflow.com/questions/12716830/xcode-4-5-no-such-file-or-directory-libcordova-a


