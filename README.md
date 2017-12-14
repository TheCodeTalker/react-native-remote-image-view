# react-native-remote-image-view

react-native-remote-image-view is a thin wrapper around [PINRemoteImage](https://github.com/pinterest/PINRemoteImage), a thread safe, performant, feature rich image fetcher for iOS.

### DISCLAIMER

**This project is currently in beta**.

Core APIs are subject to change. We encourage people to try this library out and provide us feedback as we get it to a stable state.

### Installation

#### iOS

Only installation via [CocoaPods](https://cocoapods.org) is supported.

1. `$ npm install react-native-remote-image-view --save`
2. Add the following lines to your Podfile relative to your `node_modules` path:
```
pod 'PINRemoteImage', :git => 'https://github.com/Pinterest/PINRemoteImage.git', :tag => '3.0.0-beta.10'
pod 'MSRRemoteImageView', path: '../node_modules/react-native-remote-image-view/MSRRemoteImageView.podspec'
```
3. `pod install`
4. Build and run your app either in Xcode or via the React Native cli.

<!-- 1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-remote-image-view` and add `MSRRemoteImageView.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libMSRRemoteImageView.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<
-->

## License

Copyright 2017 Michael Schneider

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
