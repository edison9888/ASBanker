ASBanker
========

Simplifies adding In App Purchases to iOS applications.

Setup
-----

**Important**

You will need to create an In App Purchase product for your app in iTunes Connect.

**Installing with [CocoaPods](http://cocoapods.org)**

If you're unfamiliar with CocoaPods there is a great tutorial [here](http://www.raywenderlich.com/12139/introduction-to-cocoapods) to get you up to speed.

1. In Terminal navigate to the root of your project.
2. Run 'touch Podfile' to create the Podfile.
3. Open the Podfile using 'open -e Podfile'
4. Add the pod `ASBanker` to your [Podfile](https://github.com/CocoaPods/CocoaPods/wiki/A-Podfile).

    	platform :ios
    	pod ASBanker'

5. Run `pod install`.
6. Open your app's `.xcworkspace` file to launch Xcode and start adding In App Purchases!

**Installing manually from GitHub**

1.	Download the `ASBanker.h` and `ASBanker.m` files and add them to your Xcode project.
2.	`#import ASBanker.h` wherever you need it.
3	Add the 'StoreKit.framework' to your project.
3.	Follow the included sample project to get started changing the products array for your product in iTunes Connect in 'ViewController.m'.

**Running the sample project**

Check out the [sample project](https://github.com/AwaraiStudios/ASBanker/tree/master/Sample) included in the repository. Just open the '.xcworkspace' file in the Sample folder and the project should build correctly.

Licence
-------

Distributed under the MIT License.

Credits
-------

This work is based on the original work of Paul Hudson, with permission.