# iOS_CheckList

Reference:

- https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/CodingGuidelines/CodingGuidelines.html

- https://github.com/raywenderlich/objective-c-style-guide

- https://github.com/raywenderlich/swift-style-guide

Some basic rules:

- If project  >= ios 8 : Swift
- Image : Must store in asset folder, 
- Split storyboard depend on scene.
- inheritance class if use multiple times (BaseViewController, BaseKeyboardVC..., BaseTextViewPlaceHolder..)
- Using correct reference object, value object
- Class function , method function
- Correct varriable scope.
- Must put tag #warning on dummy code , test code

- Remove all warning, analyse via xcode (unuse variable, #warning)

- Write unit test with some basic function, 
