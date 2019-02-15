# TapticEngineFeedback
One line to generate feedback through Taptic Engine with three diverse feedback :0
### Feature
* Category, no side effects.

### Requirements
Any Devices with Taptic Engine.

### Usage
#### Import the .h file in which you want to generate feedback.

```objective-c
#import "UIImpactFeedbackGenerator+Feedback.h"
```
#### Call the class method to make effect.

```objective-c
[UIImpactFeedbackGenerator generateFeedbackWithLightStyle];
```

### We have provided with three class methods, choose whichever you want.
```objective-c
+ (void)generateFeedbackWithLightStyle;
+ (void)generateFeedbackWithMediumStyle;
+ (void)generateFeedbackWithHeavyStyle;
```

### License
TapticEngineFeedback is released under the MIT license. See [LICENSE](https://github.com/polichan/TapticEngineFeedback/blob/master/LICENSE) for details.