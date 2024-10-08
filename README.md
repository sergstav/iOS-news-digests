# iOS-news-digests
iOS news digests 

# September 3, 2024

Send data Between iOS Apps and Extensions Using Darwin Notifications
n iOS development, app extensions run in separate processes from their containing apps. This separation poses a challenge when you need to communicate between the main app and its extensions. While NSNotificationCenter is a common choice for passing data between view controllers within the same app, it falls short when it comes to inter-process communication. Have you ever thought about how to pass data between the main app and its extension? Darwin notifications provide a powerful solution for this scenario. In this post, we’ll explore how to implement a Darwin Notifications manager and use it to facilitate real-time data transfer between a main app and its extension:\
https://ohmyswift.com/blog/2024/08/27/send-data-between-ios-apps-and-extensions-using-darwin-notifications

SwiftUI Modifiers Deep Dive: containerBackground
On this deep dive, we are exploring the containerBackground SwiftUI modifier, which was added in iOS 17:\
https://swift.mackarous.com/posts/2024/08/modifiers-container-background/

A great article about concurrency with a lot of interesting examples
Concurrency Step-by-Step: A Network Request\
https://www.massicotte.org/step-by-step-network-request

JavaScript to Swift and back: Bridging location services in WKWebView\
https://swiftlybald.com/javascript-to-swift-and-back-bridging-location-services-in-wkwebview

SwiftUI Previewable Mac
Apple added the Previewable macro to iOS 18. This generates the boilerplate wrapper view you need to preview a view with State bindings:\
https://useyourloaf.com/blog/swiftui-previewable-macro

Continuous deployment for large monorepos
A story about Uber's process of updating code
In this article, we share how we reimagined continuous deployment of microservices at Uber to improve our deployment automation and the user experience of managing microservices, while tackling some of the peculiar challenges of working with large monorepos with increasing commit volumes:\
https://www.uber.com/en-UA/blog/continuous-deployment/

# August 27, 2024

First things first. Apple announced "It's Glowtime" event. Monday, Sep 9, 10 am:\
https://www.apple.com/apple-events/

SwiftUI for Mac 2024\
https://troz.net/post/2024/swiftui-mac-2024

New Phishing Technique Bypasses Security on iOS and Android to Steal Bank Credentials
Anti-malware vendor ESET is warning of a new phishing tactic targeting iOS and Android users with web applications mimicking legitimate banking software to bypass security protections and steal login credentials:\
https://www.securityweek.com/new-phishing-technique-bypasses-security-on-ios-and-android-to-steal-bank-credentials

The Epic Games Store Launches on Mobile
Fortnite, Fall Guys, and Rocket League Sideswipe All Coming to the Epic Games Store for iPhones and Android, and to AltStore
Today the Epic Games Store is available for download on iPhones in the European Union and on Android devices worldwide. The store is launching with Fortnite, Rocket League Sideswipe and the all-new Fall Guys for mobile, and we are working to enable all developers to launch their games and apps through the Epic Games Store in the future. We are also bringing our games to independent mobile stores including AltStore PAL today:\
https://www.epicgames.com/site/en-US/news/the-epic-games-store-launches-on-mobile

Typed throws in Swift
Swift was promoted as a type-safe programming language on its very first day, and it is solid and safe in many aspects. The part of type safety that needed to be added was throwing functions. Swift 6.0 introduces typed throws, and we will learn all about them this week:\
https://swiftwithmajid.com/2024/08/20/typed-throws-in-swift/

JSON Parsing in Swift explained with code examples
JSON parsing in Swift is a common thing to do. Almost every app decodes JSON to show data in a visualized way. Parsing JSON is definitely one of the basics you should learn as an iOS developer.
Decoding JSON in Swift is quite easy and does not require any external dependencies. The basic APIs that come with Swift will be enough to do the job, so let’s dive in:\
https://www.avanderlee.com/swift/json-parsing-decoding

Let’s build iOS 18’s navigation title card in SwiftUI
iOS 18 standardizes a design pattern that could be called “navigation title cards”, for lack of an established HIG term. In their simplest form, these cards appear at the top of a list of content and provide brief explanatory text:\
https://jeffverkoeyen.com/blog/2024/08/24/iOS-18-Navigation-Title-Cards

# August 13, 2024
We all know about Swift for iOS, MacOS, watchOS development and even for backend development. But what about embedded? Here it is
Embedded Swift Tutorial - Getting Started (Everything you need to know)
Apple announced Embedded Swift development at WWDC 2024. This new development target allows you to start coding for non-Apple hardware using Swift:\
https://blog.supereasyapps.com/embedded-swift-tutorial-getting-started-everything-you-need-to-know

Navigation Patterns in SwiftUI
Navigation has often been a challenge in SwiftUI applications. Initially, SwiftUI introduced NavigationView, which was later replaced by NavigationStack in iOS 16.
NavigationStack enhanced navigation by enabling dynamic and programmatic routing, and it also offered ways to centralize routes for the entire application. In this article, I’ll explore common navigation patterns that can be employed when building SwiftUI applications:\
https://azamsharp.com/2024/07/29/navigation-patterns-in-swiftui.html

Entry Macro for Custom SwiftUI Environment Values
The Entry macro reduces the boilerplate when customizing the SwiftUI environment:\
https://useyourloaf.com/blog/entry-macro-for-custom-swiftui-environment-values

How to upload assets using the App Store Connect API
When you create a new version of your app in App Store Connect, you might also need to upload new assets like screenshots or previews for the App Store. You can do this manually on the App Store Connect website, but if you have a lot of localizations to support and your assets change often across versions, this can be a tedious, error-prone, and time-consuming process:\
https://www.runway.team/blog/how-to-upload-assets-using-the-app-store-connect-api

Truncating Text In SwiftUI
Text is the most common kind of content that apps contain. We deal with all sorts of text length everyday, but when it comes to long text we often need to cut it off and display just a part of it. Along with that, users usually get an option to expand and view the long text, or collapse and keep it truncated.
In this post we are going to demonstrate two ways that will let you achieve truncation easily, and an additional approach where you can simulate (fake) truncation by fetching and presenting a substring of the original string. As a bonus chapter, I’ll also show you how to expand and collapse truncated text, mostly because truncation and text expansion go together as features into an app:\
https://serialcoder.dev/text-tutorials/swiftui/truncating-text-in-swiftui

# August 6, 2024
App design: 5 benefits of using system components
Building custom elements and ignoring the sometimes boring system components during app design can be appealing. However, these boring elements have many benefits you might not be aware of.
If you’ve read many of my technical articles, you might be surprised to hear that I’ve actually done a bachelor’s degree in Communication and Multimedia Design (CMD), also known as Interactive Media, in Amsterdam. I’ve had to teach myself coding on the side, resulting in a great mix of design and coding knowledge. In today’s article, I’ll share a few reasons why system components should not be overlooked:\
https://www.avanderlee.com/optimization/app-design-5-benefits-of-using-system-components

Pickup in 3 minutes: Uber’s implementation of Live Activity on iOS
The 2022 WWDC keynote brought an unexpected surprise when Apple™ unveiled the new Live Activities feature, using Uber’s Rider app as a prominent example. This announcement generated excitement for the feature to come and set the stage for an exhilarating journey for our team.
What follows is the story of how we started designing for surfaces outside the app, the engineering problems we had to solve along the way, and ultimately how we measurably improved the experience of riders and drivers:\
https://www.uber.com/en-LB/blog/live-activity-on-ios/?uclick_id=a322da25-5f8e-483c-ab44-fc54cb783c3c

Scrolling pickers in SwiftUI
Today we’ll be exploring the features that ScrollView carrying around since iOS 17 by building a value picker.
Breath some inspiration from this post and let’s get started:\
https://uvolchyk.medium.com/scrolling-pickers-in-swiftui-de4a9c653fb6

Displaying Data with Table (Part I)
One of the most traditional ways of displaying data is through a table. Think about having to create one in a document, working with a spreadsheet, or (for the experienced dev) a database. That’s why the Table component is a powerful tool in the SwiftUI framework. It doesn’t take much code to get data beautifully laid out in our app.
A little more here and there and we can quickly add on features and styles to enhance the UX. We’ll explore that in Part II:\
https://captainswiftui.substack.com/p/displaying-data-with-table-part-i

Olympic Logo in SwiftUI\
https://medium.com/@alessandromanilii/olympic-logo-in-swiftui-dee37cbd53f1

How often do you use lazy keyword in your code? Maybe you need to refresh your knowledge about it? Here is the article for you
Lazy var in Swift explained with code examples
A lazy var is a property whose initial value is not calculated until the first time it’s called. It’s part of a family of properties in which we have constant properties, computed properties, and mutable properties.
A lazy property might be lesser known to beginners in Swift but are actually super valuable once you know when and how to use them. There are a few important things to learn so you know when to use which type of property:\
https://www.avanderlee.com/swift/lazy-var-property

#Books
If you ever wondered about macOS development here is a book for you:\
https://troz.net/books/macos_tutorials/

# 30 July, 2024
If you ever thought about going indie do not miss this article from Antoine var der Lee about this success story:\
https://www.avanderlee.com/general/from-side-project-to-going-indie

A Paywall Optimization Success Story
The motivation, process, and results of a recent paywall experiment that significantly boosted conversions for Foodnoms:\
https://ryanashcraft.com/paywall-optimization-success-story/

Async await in Swift: The Full Toolkit
Today, we're going through the many techniques in the Swift Concurrency toolkit. We'll discuss theory when it's appropriate, but for each tool we'll also provide a context where it might be the best solution:\
https://www.emergetools.com/blog/posts/swift-async-await-the-full-toolkit

Unfold's Modern Mobile Release Process and the Subtle Art of Making Them Boring
On the Unfold team at Squarespace, we build our mobile app for both iOS and Android, and our releases don't require much in the way of manual intervention or human oversight. In fact, we don’t have to give releases much thought at all:\
https://engineering.squarespace.com/blog/2024/unfolds-modern-mobile-release-process-and-the-subtle-art-of-making-them-boring

If you ever worked with Objective-C, you probably have some opinion about using it, check this article about comparison Objective-C and Swift
Swift vs. Objective-C: Which is Better for iOS Development:\
https://dev.to/ravi_makhija/swift-vs-objective-c-which-is-better-for-ios-development-om3

Unobtrusive and testable issue reporting
Developers from PointFree are happy to anounce about creating a new library: Issue Reporting. This library provides tools to report issues in your application and library code as Xcode runtime warnings, breakpoints, assertions, and do so in a testable manner:\
https://www.pointfree.co/blog/posts/147-unobtrusive-and-testable-issue-reporting

# July 23, 2024
Let's start this digest with something unusual - Mac development using Go 🙂
How I build simple Mac apps using Go\
https://dev.to/progrium/how-i-build-simple-mac-apps-using-go-104j

And one more about Mac development. Great article from Jordi Bruin about all the pros and benefits of development for Mac
Why macOS Development is Perfect for Indie Developers
Building apps for macOS offers developers a fantastic opportunity to expand their skills, create useful utilities to solve their problems, and begin their journey as indie developers:\
https://www.avanderlee.com/swiftui/macos-development-powerful-utilities

Adding values to the SwiftUI environment with Xcode 16’s Entry macro
Adding custom values to SwiftUI’s environment has never been very hard to do to. However, the syntax for doing it is verbose and easy to forget. To refresh your mind, take a look at this post where we explain how to add your own environment values to a SwiftUI view:\
https://www.donnywals.com/adding-values-to-the-swiftui-environment-with-xcode-16s-entry-macro

The video you should definitely see - the interview with Chris Lattner the creator of the Swift language and his thoughts about current Swift state:\
https://www.youtube.com/watch?v=ovYbgbrQ-v8&ab_channel=ThePrimeTime

And one more about Swift problems - Data race safety\
https://kean.blog/post/swift-6

If you ever wondered what is the difference between Some and Any make sure to check this article
Some vs Any\
https://mfaani.com/posts/swift/some-vs-any

# July 16, 2024
Some tips & tricks with the new iOS 18 ScrollView API
Pagination, hiding navigation and tab bar & more
iOS 18 brings a host of new APIs for the ScrollView; it’s now better than ever! From reading the exact position to listening to the scroll view status, you can (mostly) do it all:\
https://dimillian.medium.com/some-tips-tricks-with-the-new-ios-18-scrollview-api-95632b41bc8e

3 Rs of Software Architecture for iOS based in SwiftUI
After over 50 years of software engineering, we still haven't settled on a precise definition of software architecture. It remains the art within computer science, persistently evading our efforts to pin it down. Nevertheless, its importance to the industry and applications is undeniable. To read more:\
https://dev.to/maatheusgois/3-rs-of-software-architecture-for-ios-based-in-swiftui-c6j

List or LazyVStack: Choosing the Right Lazy Container in SwiftUI
In the world of SwiftUI, List and LazyVStack, as two core lazy containers, offer robust support for developers to display large amounts of data. However, their similar performance in certain scenarios often causes confusion among developers when making a choice. This article aims to analyze the characteristics and advantages of these two components to help you make a better decision:\
https://itnext.io/list-or-lazyvstack-choosing-the-right-lazy-container-in-swiftui-27f5b8272dae

Using PreviewModifier to build a previewing environment
Xcode 16 and iOS 18 come with a feature that allows us to build elaborate preview environments using a new PreviewModifier protocol. This protocol allows us to define objects that can create a single context or environment that’s cached and used across your SwiftUI previews:\
https://www.donnywals.com/using-previewmodifier-to-build-a-previewing-environment

Blend Modes in SwiftUI
Blend modes play a crucial role in digital design, enabling designers to easily create complex visual effects like overlays and textures. They're essential for tasks like photo manipulation, creating lighting effects, and adding depth to images.
Blend modes, as the name suggests, blends the colors of multiple layers of pixels using mathematical formulas to determine each pixel's influence on the final image. You can combine any number of layers, but at a minimum, you'll need 2 layers - a base layer and a blend layer to create a blend mode effect:\
https://digitalbunker.dev/blend-modes-in-swiftui

After two rejections, Apple approves Epic Games Store app for iOS\
https://arstechnica.com/gadgets/2024/07/report-apple-approves-epic-games-store-on-ios-in-europe/

# July 9, 2024
Vulnerabilities in CocoaPods Open the Door to Supply Chain Attacks Against Thousands of iOS and MacOS Applications
Multiple vulnerabilities affecting the CocoaPods ecosystem, have been discovered, posing a major risk of supply chain attacks:\
https://www.evasec.io/blog/eva-discovered-supply-chain-vulnerabities-in-cocoapods

Let's dive into some iOS apps history 🙂 Let's read how Uber's iOS and Android applications were created. 
Brief History of Scaling Uber\
https://www.linkedin.com/pulse/brief-history-scaling-uber-josh-clemm-dfqgc/

SwiftUI can be a bit... eager
When writing an application using AppKit or UIKit you feel can confident as to when views are created and released. Your code takes explicit actions for that to happen. SwiftUI is a big more nebulous. Let's look at a typical example. Below is a simple SwiftUI application that shows a partial list of SFSymbols and allows you to tap on one to see a larger version:\
https://www.attributedstrings.com/swiftui-can-be-a-bit-eager

A Summary Of How To Pass Data To SwiftUI Environment
The SwiftUI environment is an in-memory shared storage among all views within a view hierarchy. Thanks to it, various parts of an app can access shared data easily, allowing for better state management which is fundamental to SwiftUI. The environment simplifies data flow by just making it available to views, while each individual view can read or update only the pieces of data that’s interested in. In general, the environment lifts a big load of sharing data among views, it helps us write cleaner code, but most importantly, it lets us focus more on the views and the user interface:\
https://serialcoder.dev/text-tutorials/swiftui/a-summary-of-how-to-pass-data-to-swiftui-environment

Mastering ScrollView in SwiftUI. Scroll Phases
This year, the SwiftUI framework introduced several new scrolling APIs, allowing us to track and tune everything in a scroll view. This week, we will discuss monitoring scroll phases in SwiftUI:\
https://swiftwithmajid.com/2024/07/02/mastering-scrollview-in-swiftui-scroll-phases

WebSocket tutorial using Swift and Hummingbird
A great tutorial about how to create a server and a client using WebSockets and Hummingbird framework on Swift:\
https://swiftonserver.com/websocket-tutorial-using-swift-and-hummingbird
