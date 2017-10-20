# SmartEffectPicker

[![GitHub release](https://img.shields.io/github/release/ShockUtility/SmartEffectPicker.svg)](https://github.com/ShockUtility/SmartEffectPicker)
[![Version](https://img.shields.io/cocoapods/v/SmartEffectPicker.svg?style=flat)](http://cocoapods.org/pods/SmartEffectPicker)
[![License](https://img.shields.io/cocoapods/l/SmartEffectPicker.svg?style=flat)](http://cocoapods.org/pods/SmartEffectPicker)
[![Platform](https://img.shields.io/cocoapods/p/SmartEffectPicker.svg?style=flat)](http://cocoapods.org/pods/SmartEffectPicker)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

```objc
    [SmartEffectPicker startEffect:self
                             title:@"Effect"
                        ourceImage:pickedImage
                         completed:^(UIImage *effectedImage) {
                             if (effectedImage != nil) {
                                 self.imageView.image = effectedImage;
                             }
                         }];
```

## Requirements

[GPUImage](https://github.com/BradLarson/GPUImage)

## Installation

SmartEffectPicker is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'SmartEffectPicker'
```

## Author

ShockUtility, shock@docs.kr

## License

SmartEffectPicker is available under the MIT license. See the LICENSE file for more info.
