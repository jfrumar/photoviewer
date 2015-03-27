# Photo Viewer  
> This plugin is intended to show a picture from an URL into a Photo Viewer with zoom features.

### Fork overview
This fork was created to strip out the iOS source - it doesn't work well with Cordova because it uses Cocoapods (which breaks the project).

### Android
> Out of the box

### iOS
> On iOS is being used a CocoaPod Library so, install CocoaPod and after install the plugin run the pod install in the iOS folder  
> pod install  
> Remember to add $(inherited) into OTHER_LDFLAGS