# Lookback iOS Flutter
Flutter plugin for the Lookback iOS SDK
https://pub.dev/packages/lookback_ios_flutter
## Description
[Lookback](https://lookback.io/) is a product tool that helps you engage your users while they use your product. To use Lookback on iOS you must use their SDK and add a small about of Objective-C/Swift code.
This library allows you to add Lookback as a pub dependency in your Flutter app by adding 1 line in your pubspec.yaml and allows you to avoid writing any native code.
## Why iOS only?
There is no Android part of this plugin because Lookback does not require an SDK on Android. Read more about that [here](https://help.lookback.io/installing-the-ios-sdk/overview-of-the-ios-sdk).
## How to use
1. Add the dependency to your pubspec.
```
dependencies:
  lookback_ios_flutter: ^0.1.0
```
2. Follow the Lookback [documentation](https://help.lookback.io/installing-the-sdk/configuring-lookback/configuring-lookback-participate), skip step 1. You will need to open your iOS project in Xcode.
## Features
- [x] Pub package brings in Lookback CocoaPods
- [x] Register openURL for starting a participate link session
- [ ] Investigate approach for Custom View Names
- [ ] Investigate approach for Private Views
- [ ] Implement setupWithAppToken, shakeToRecord, feedbackBubbleVisible, etc