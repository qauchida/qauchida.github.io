---
layout: essay
type: essay
title: Native App Frameworks
# All dates must be YYYY-MM-DD format!
date: 2020-05-19
labels:
  - React
  - TypeScript
  - JavaScript
  - NativeScript
  - Flutter

---	
I’ve only used React to make web apps. I have limited brainspace so I’d rather just stick with what I know about React (which isn’t much). But technology is always changing so maybe there’s something new out there worth learning.

![React Native Logo](https://reactnative.dev/img/header_logo.svg)
## [React Native](https://reactnative.dev/)

It’s called React because it’s reactive, meaning the appearance of the page will change without manually refreshing it. Think of this like a mantra and repeat it before you go to bed every night, “Change in props to change state to trigger rerender.” 

React Native is a little different than React, as it uses native components instead of web components. 

### Pros:
* HUGE Community
* Used to make apps for FaceBook, Instagram, Discord and more
* Can make one app for IOS, Android and web instead of making one for each specific mobileOS

### Cons:
* still will have to learn React Native Specifics
* React Native was made by FaceBook and FaceBook is evil

![NativeScript Logo](https://www.nativescript.org/images/default-source/logos/nativescript-logo.png?sfvrsn=2)
## [Native Script](nativescript.org)
NativeScript is used to build native android and IOS mobile apps. You can use a combination of Angular and NativeScript, Vue.js and NativeScript, or JavaScript/TypeScript and NativeScript. 

I tried out a sample from NativeScript’s website but it required me to download 2 different mobile apps, NativeScript Preview and NativeScript Playground. The sample applications look and function alright but NativeScript doesn't have as many compa


![And here's a table from React NativeScript creator Jamie Birch comparing React and React NativeScript.](https://d2odgkulk9w7if.cloudfront.net/images/default-source/blogs/react-ns-differences.png?sfvrsn=46850cfe_0)

### Pros
* lots of free working examples and samples with code [on NativeScript MarketPlace](https://market.nativescript.org/)
* React NativeScript combines React and NativeScript

### Cons
* React NativeScript has not been fully developed (and is community developed)
* Learning curve with Angular or Vue.js

![Flutter Logo](https://flutter.dev/assets/flutter-lockup-c13da9c9303e26b8d5fc208d2a1fa20c1ef47eb021ecadf27046dea04c0cebf6.png)
## [Flutter](https://reactnative.dev/)

Flutter is Google’s UI toolkit and it uses a language called Dart. While I’ve never heard of Dart before, there is decent, well organized documentation for it. Flutter has documentation specific for developers who have experience in React and who now want to learn Flutter. 


[Here’s a fairly recent article about Flutter developers.](https://medium.com/flutter/what-are-the-important-difficult-tasks-for-flutter-devs-q1-2020-survey-results-a5ef2305429b)

### Pros
* Used to make apps for Google, Ebay and more
* Decent Documentation
* Build Native apps for mobile, web and desktop from single codebase
* Quinne loves Google UIs
* Hot Reload
* Beautiful built-in animations

### Cons 
* Smaller community than React Native
* Learning curve

### Recommendations

When giving a recommendation, it’s important to think about the needs of the user while also acknowledging certain technical restraints. CSExplore will most likely be accesed through a mobile device and is assumed to be an IOS/Android app. The problem with that is that users will have to download the app to access the contents if there is no mobile web version. 

#### Recommendation Big Gamble: Flutter
As a user, I adore Google apps UI. It's simple, clean and functional (at least from the user standpoint). But trying to use Flutter is a huge gamble for our team. I'm pretty sure none of us has learned Dart so we'd all be starting at the beginning. Will it be worth it to learn about Dart and Flutter just to make a beautiful app? Having a beautiful app that's also functional can help show these students what's possible at (just) the college level. Just like you would never trust a skinny chef, why would you trust a janky app to teach you about Computer Science?

### Recommendation Play It Safe: React Native
The development team for CSExplore has experience with React so making an app with React Native shouldn't be too much of a stretch. Using React Native is less of a gamble.


## Articles and APIs

* [React Native vs NativeScript vs Flutter](https://academind.com/learn/flutter/react-native-vs-flutter-vs-ionic-vs-nativescript-vs-pwa/)
* [Here’s a Medium article comparing React Native and NativeScript](https://medium.com/@techaffinity/react-native-vs-nativescript-7ebe0ecdc232)

