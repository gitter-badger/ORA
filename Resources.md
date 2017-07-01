# Course objectives

Uber-Objective is to get moving under your own steam. To give you a birds-eye view
 of the world of iOS-dev so that you can direct your dive-in.

We'll cover:  
 - Remote Linux WebServer / HTML / JS / ssh / etc.
 - Swift language (plus C -> ObjC -> Swift)
 - XCode -- build code to device, debug
 - iOS API -- navigate Apple's documentation
 - Using available **Resources** -- Stack Overflow / IRC / Apple Dev site: doc, ibooks, forums / ...
 - collaboration using GitHub / Gitter
 - alternative frameworks (Unity3D, JUCE) https://clutch.co/app-development/cross-platform


## SWIFT

https://developer.apple.com/library/content/documentation/Swift/Conceptual/Swift_Programming_Language/  
Take the tour (using the playground), Language Guide  
Notice iBooks (at top) -- same material! Download the iBook!

QuickRef: https://www.gitbook.com/book/azuritul/swift-syntax-quick-reference


## iOS AppDev with SWIFT

Building Your First Swift App Video (6min) https://developer.apple.com/swift/blog/?id=16

https://developer.apple.com/library/content/referencelibrary/GettingStarted/DevelopiOSAppsSwift/  
This is the material my PowerPoint slides cover.
Notice it is bizarrely hidden.  It is a 'hello world' of iOS appdev, but try finding it from the main page.
  In fact try finding it from the parent 'Guides and Sample Code' page. It is absolutely buried!

Skimming these guides:
 * iPhoneOSTechOverview - Look at the bottom of the intro page & see guides for Human Interface guidelines & App distribution
 * VideoSnake
 * SpeakToMe: Using Speech Recognition with AVAudioEngine
 * SpeedSketch: Leveraging touch input for a drawing application
 * Photo Capture Programming Guide
 * iAd Programming Guide
 * iOS Technology Overview <-- notice this is just the same as iPhoneOSTechOverview i.e. This whole thing is a mess
 * Teslameter <-- NICE but Obj-C
 * **MyLife: A simple app for starting iOS development**
 
_(Remember to set project settings -> build settings -> development team)_

https://itunes.apple.com/us/book/intro-to-app-development-with-swift/id1118575552?mt=11
https://itunes.apple.com/us/book/app-development-with-swift/id1219117996?mt=11


## Possibles:

https://itunes.apple.com/gb/book/swift-coding-challenges/id1177738461?mt=11  
https://www.hackingwithswift.com/read -- online book by same author

http://blog.udacity.com/2015/10/14-essential-swift-ios-resources.html

https://github.com/matteocrippa/awesome-swift  
https://github.com/vsouza/awesome-ios <-- other good Lists (see open source)


# Swift

```
class XY {
    init(_x:Float,_y:Float) {x=_x; y=_y}
    var x:Float, y:Float
}

var x = XY(_x: 3,_y: 4)

extension XY {
    func mag2()->Float {return x*x + y*y}
}

x.mag2()
```

Extend String to have an isPalendromic() method
Complex maybe?

Mandelbrot https://developer.apple.com/swift/blog/?id=26 -> https://github.com/palmerc/Mandelbrot-Swift-Playground

