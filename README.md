iOS-Projects-Catalogue
======================

This is my collection of iOS/Objective-C Open Source projects. I prefer keeping it in a separate repository to have a fast access to any projects I recently Github-starred or explored.

It will grow as fast as it is possible with my ability to add new projects I am already aware of and my ability to explore new projects around the net, Github, etc.

If you liked it, feel free to suggest any new projects that are not present in the current list.

Also I keep another catalogue of projects: it contains [the list of candidates for this catalogue](https://github.com/stanislaw/iOS-Projects-Catalogue/blob/master/CANDIDATES.md). After I am sure enough that a particular candidate-project deserves its place here, I move it here from the list of Candidates.

Note! This catalogue also includes a number of projects which are not open-source but are still somehow related to a development of iOS/Objective-C applications.

----

## <a name="Objective-C-And-Cocoa"></a> Objective-C and Cocoa

### Frameworks

* [GNUstep](https://github.com/gnustep/gnustep-base)

> GNUstep is a mature Framework, suited both for advanced GUI desktop applications as well as server applications. The framework closely follows Apple's Cocoa (formerly NeXT's OpenStep) APIs but is portable to a variety of platforms and architectures.

* [AFNetworking](http://afnetworking.com/)

> A delightful networking framework for iOS and OSX

* [RestKit](https://github.com/RestKit/RestKit)

> RestKit is a framework for consuming and modeling RESTful web resources
on iOS and OS X 

* [ReactiveCocoa](https://github.com/ReactiveCocoa/ReactiveCocoa)

> A framework for composing and transforming streams of values

* [NimbusKit](http://nimbuskit.info/)

> Nimbus is a toolkit for experienced iOS software designers. It provides well-documented, modular components that solve a number of common iOS software requirements. This includes: a rich text label with hyperlinks; a web view controller; a simple approach to table models, radio groups, and table actions; standardized interapp communication, and powerful debugging tools, amongst many other features.

* [epam/road-ios-framework](https://github.com/epam/road-ios-framework)

> ROAD - Rapid Objective-C Applications Development
 
### Extensions for Objective-C and Cocoa frameworks

* [libextobjc](https://github.com/jspahrsummers/libextobjc)

> A Cocoa library to extend the Objective-C programming language.

* [ObjectiveSugar](https://github.com/mneorr/ObjectiveSugar)

> ObjectiveC additions for humans. Ruby style.

* [pandamonia/BlocksKit](https://github.com/pandamonia/BlocksKit)

> The Objective-C block utilities you always wish you had.

* [QSKit](https://github.com/quartermaster/QSKit)

> Q Branch’s collection of Cocoa categories and utilities.

### <a name="Objective-C-And-Cocoa/Promises"></a> Libraries implementing Promises (Futures) pattern

* [RXPromise](https://github.com/couchdeveloper/RXPromise)

> An Objective-C Class which implements the Promises/A+ specification.

### Macros utilities

* [robrix/RXPreprocessing](https://github.com/robrix/RXPreprocessing)

> A variety of utilities for the C preprocessor.

* [JREnum](https://github.com/rentzsch/JREnum)

> macros that automate vending an NSString given an enum value (f.x.
MyEnumToString(value))

### Conventions / Style guides

* [github/objective-c-conventions](https://github.com/github/objective-c-conventions)

> Coding conventions for Objective-C projects.

* [NYTimes/objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide)

> The New York Times Mobile Team’s Objective-C Style Guide.

### Low-level

* [nickhutchinson/libdispatch](https://github.com/nickhutchinson/libdispatch)

> Linux port of Apple's open-source concurrency library

* [rentzsch/mach_inject](https://github.com/rentzsch/mach_inject)

> interprocess code injection for Mac OS X

* [rentzsch/mach_override](https://github.com/rentzsch/mach_override)

> runtime function overriding for Mac OS X

### Other

* [EvgenyKarkan/EKAlgorithms](https://github.com/EvgenyKarkan/EKAlgorithms)
 
> EKAlgorithms contains some well known CS algorithms and other stuff.

----

## Networking

### HTTP servers

* [CocoaHTTPServer](https://github.com/robbiehanson/CocoaHTTPServer)

> A small, lightweight, embeddable HTTP server for Mac OS X or iOS
applications

### Socket libraries

* [CocoaAsyncSocket](https://github.com/robbiehanson/CocoaAsyncSocket)

> Asynchronous socket networking library for Mac and iOS

* [SocketRocket](https://github.com/square/SocketRocket)
  
> A conforming Objective-C WebSocket client library.

* [fast-socket](https://github.com/dreese/fast-socket)

> A fast, synchronous Objective-C wrapper around BSD sockets for iOS and
OS X.

* [CocoaPort](https://github.com/chrisdevereux/CocoaPort)

> An asynchronous, futures-based distributed objects library for Objective-C

### Network logging

* [AFHTTPRequestOperationLogger](https://github.com/AFNetworking/AFHTTPRequestOperationLogger)

> AFNetworking Extension for HTTP Request Logging

### Other

* [tonymillion/Reachability](https://github.com/tonymillion/Reachability)

> ARC and GCD Compatible Reachability Class for iOS and MacOS. Drop in
replacement for Apple Reachability

* [CocoaSPDY](https://github.com/twitter/CocoaSPDY)

> SPDY for iOS and OS X

----

## Data layer

* [github/Mantle](https://github.com/github/Mantle)

> Model framework for Cocoa and Cocoa Touch

* [RestKit/RKValueTransformers](https://github.com/RestKit/RKValueTransformers)

> A powerful value transformation API extracted from RestKit

* [mattt/TransformerKit](https://github.com/mattt/TransformerKit)

> A block-based API for NSValueTransformer, with a growing collection of
useful examples.

* [nicklockwood/FastCoding](https://github.com/nicklockwood/FastCoding)

> A faster and more flexible binary file format replacement for Property
Lists and JSON

* [nicklockwood/AutoCoding](https://github.com/nicklockwood/AutoCoding)

> AutoCoding is a category on NSObject that provides automatic support
for NSCoding and NSCopying to every object.

### SQLite-based projects / Alternatives to CoreData

* [FMDB](https://github.com/ccgus/fmdb)

> A Cocoa / Objective-C wrapper around SQLite

* [FCModel](https://github.com/marcoarment/FCModel)

> An alternative to Core Data for people who like having direct SQL access.

* [ObjectiveRecord](https://github.com/mneorr/ObjectiveRecord)

> A lightweight Active Record - style of managing CoreData objects.

* [iActiveRecord](https://github.com/AlexDenisov/iActiveRecord)

> ActiveRecord for iOS without CoreData, only SQLite.

### Key-value store

* [YapDatabase](https://github.com/yaptv/YapDatabase)
 
> YapDatabase is a "key/value store and MORE" built atop sqlite for iOS & Mac.

* [NyaruDB](https://github.com/kelp404/NyaruDB)

> A simple NoSQL database(key-value pair) in Objective-C. It runs on iOS and OS X.

* [NULevelDB](https://github.com/nulayer/NULevelDB)

> Objective-C interface to Google's LevelDB key/value embedded database

* [kvdb](https://github.com/colinyoung/kvdb)

> a key-value object store backed by sqlite3 for ios

----

## <a name="DebuggingTools"></a> Debugging tools

* [VMInstrumenter](https://github.com/vittoriom/VMInstrumenter)

> A simple Objective-C singleton to instrument, protect, trace, and
suppress selectors at runtime

### <a name="DebuggingTools/Logging"></a> Logging

* [NSLogger](https://github.com/fpillet/NSLogger)

> A modern, flexible logging tool

* [CocoaLumberjack](https://github.com/robbiehanson/CocoaLumberjack)

> A fast & simple, yet powerful & flexible logging framework for Mac and iOS

* [JRLog](https://github.com/rentzsch/JRLog)

> Simple but flexible Log4J-like logging system for Objective-C

* [UrbanApps/UALogger](https://github.com/UrbanApps/UALogger)

> A powerful and flexible logging utility for Mac/iOS apps

* [MTLog](https://github.com/icanzilb/MTLog)

> NSLog replacement for coders!

----

## Testing

### Testing frameworks

* [Kiwi](https://github.com/allending/Kiwi)

> BDD for iOS

* [Cedar](https://github.com/pivotal/cedar)

> BDD-style testing using Objective-C

### Test Automation

* [Frank](https://github.com/moredip/Frank)

> Automated acceptance tests for native iOS apps.

* [KIF](https://github.com/kif-framework/KIF)

> Keep It Functional - An iOS Functional Testing Framework

* [calabash-ios](https://github.com/calabash/calabash-ios)

> Calabash is an automated testing technology for Android and iOS native
and hybrid applications.

### Stubbing tools

* [OHHTTPStubs](https://github.com/AliSoftware/OHHTTPStubs)

> Stub your network requests easily! Test your apps with fake network data and custom response time, response code and headers!

* [Nocilla](https://github.com/luisobo/Nocilla)

> Testing HTTP requests has never been easier. Nocilla: Stunning HTTP
stubbing for iOS and Mac OS X.

### VCR tools

* [VCRURLConnection](https://github.com/dstnbrkr/VCRURLConnection)

> VCRURLConnection is an iOS and OSX API to record and replay HTTP
interactions, inspired by VCR for ruby

### Other

* [neilco/RedGreen](https://github.com/neilco/RedGreen)

> RedGreen is an extension library for SenTestKit that makes the test
output easier to parse by humans.

* [mneorr/XCPretty](https://github.com/mneorr/XCPretty)

> Flexible and fast xcodebuild formatter

----

## Deployment

* [Air-Test](https://github.com/rjyo/Air-Test)

> A tool that will make a lot of iPhone/iPad developers' life easier. It
shares your app over-the-air in a WiFi network. Bonjour is used and no
configuration is needed.

----

## Command-line tools

* [xctool](https://github.com/facebook/xctool)

> xctool is a replacement for Apple's xcodebuild that makes it easier to build and test iOS and Mac projects.

* [nomad-cli](http://nomad-cli.com/)
> world-class command line utilities for iOS development
  * [Cupertino](https://github.com/nomad/cupertino)
  
    > Automate administrative tasks that you would normally have to do
through the Apple Dev Center website. Life's too short to manage device
identifiers by hand!
  
  * [Houston](https://github.com/nomad/houston)
  
    > Send push notifications from the command line. Simply provide your
credentials, construct your message, and 3...2...1... blastoff.

  * [Dubai](https://github.com/nomad/dubai)

    > Generate Passbook .pkpass files with ease. Rapidly iterate on the
design and content of your passes, or generate one-offs on the fly.

  * [Venice](https://github.com/nomad/venice)

    > Secure your In-App-Purchases by verifying App Store purchase
receipts, and retrieving the information associated with receipt data.

  * [Shenzhen](https://github.com/nomad/shenzhen)

    > Create development builds and then distribute their .ipa files over
TestFlight, HockeyApp, Amazon S3, or FTP. Get new builds out to testers
and enterprises in seconds.

* [phonegap/ios-sim](https://github.com/phonegap/ios-sim)

> Command Line Launcher for the iOS Simulator.

* [Sim-Launcher](https://github.com/moredip/Sim-Launcher)

> tiny little sinatra app to allow launching an iOS app in the simulator via HTTP

* [fruitstrap](https://github.com/ghughes/fruitstrap/)

> Install and debug iPhone apps from the command line, without using
Xcode

----

## Analytics

* [AnalyticsKit](https://github.com/twobitlabs/AnalyticsKit)

> Analytics framework for iOS

* [ARAnalytics](https://github.com/orta/ARAnalytics)

> Simplify your iOS analytics

### Analytics providers

* [Flurry](http://www.flurry.com)

> INDUSTRY-LEADING APP ANALYTICS FOR FREE

* [Crashlytics](https://github.com/crashlytics)

> ...the most powerful, yet lightest weight crash reporting solution.

* [mixpanel/mixpanel-iphone](https://github.com/mixpanel/mixpanel-iphone)

> iPhone tracking library for Mixpanel Analytics. http://mixpanel.com

* [Countly/countly-sdk-ios](https://github.com/Countly/countly-sdk-ios)

> Countly Mobile Analytics - iOS SDK http://count.ly

----

## iOS7

* [shu223/iOS7-Sampler](https://github.com/shu223/iOS7-Sampler)

> Code examples for the new functions of iOS 7.

* [ShinobiControls/iOS7-day-by-day](https://github.com/ShinobiControls/iOS7-day-by-day)

> Repo containing the sample projects associated with the iOS7 Day-by-Day
blog series


----

## UI

* [ADTransitionController](https://github.com/applidium/ADTransitionController)

> UINavigationController with custom transitions

* [nicklockwood/FXImageView](https://github.com/nicklockwood/FXImageView)

> FXImageView is a class designed to simplify the application of common visual effects such as reflections and drop-shadows to images, and also to help the performance of image loading by handling it on a background thread.
 
### UIKit extensions

* [hfossli/AGGeometryKit](https://github.com/hfossli/AGGeometryKit)

> A bundle of small classes which enriches your possibilities with UIKit
and CoreAnimation.

* [UIImage-Categories](https://github.com/mbcharbonneau/UIImage-Categories)
   
> An fork of Trevor Harmon's UIImage category methods, updated for the
latest versions of iOS.

### Maps

#### Clustering

* [kingpin](https://github.com/itsbonczek/kingpin)

> A drop-in MapKit/MKAnnotation pin clustering library for MKMapView on iOS

* [ADClusterMapView](https://github.com/applidium/ADClusterMapView)

> MKMapView with clustering

* [OCMapView](https://github.com/yinkou/OCMapView)

> Simple and easy to use clustering mapView for iOS

---- 

## Graphics

* [SVGKit](https://github.com/SVGKit/SVGKit)

> Display and interact with SVG Images on iOS / OS X, using native
rendering (CoreAnimation)

----

## Audio

* [EZAudio](https://github.com/syedhali/EZAudio)

> An iOS and OSX audio visualization framework built upon Core Audio useful for anyone doing real-time, low-latency audio processing and visualizations.

* [novocaine](https://github.com/alexbw/novocaine)

> Painless high-performance audio on iOS and Mac OS X. http://alexbw.github.com/novocaine/

* [AudioModem](https://github.com/applidium/AudioModem)

> Transfer data using microphone/speaker on iOS devices

----

## Applications

### Graphics

* [Inkpad](https://github.com/sprang/Inkpad)

> Vector illustration app for the iPad.

* [Brushes](https://github.com/sprang/Brushes)

> Painting app for the iPhone and iPad.

### Other

* [mbus](https://github.com/jonahgrant/mbus)

> iOS implementation of the University of Michigan's bus dispatch system

* [mtigas/iOS-OnionBrowser](https://github.com/mtigas/iOS-OnionBrowser)

> An open-source, privacy-enhancing web browser for iOS, utilizing the
Tor anonymity network



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/stanislaw/ios-projects-catalogue/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

