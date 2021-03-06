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
The big thing to do these days is to create apps. I remember 10 years ago when I was starting high school, everyone wanted to make apps because of Angry Birds. "True computer people" thought mobile apps were just another passing fad. But today, a smartphone has become a necessity and with it, mobile apps. I’ve only used React to make web apps and I have limited brainspace so I’d rather just stick with what I know about React (which isn’t much). But technology is always changing so maybe there’s something new out there worth learning.


<img src="https://reactnative.dev/img/header_logo.svg"  width="300" height="300" />

## [React Native](https://reactnative.dev/)

It’s called React because it’s reactive, meaning the appearance of the page will change without manually refreshing it. Think of this like a mantra and repeat it before you go to bed every night, “Change in props to change state to trigger rerender.” 

React Native is a little different than React, as it uses native components instead of web components. However, it still follows the React lifecycle and IOS/Android specifc lifecycles can get very convoluted. Since 2015, React Native has been used to created tons of mobile applications such as Facebook, Instagram, Pinterest and more. The neatest thing about React (and the other frameworks mentioned later) is that it uses a single codebase to make both IOS and Android apps. The old way involved making 2 sets of code for 1 app if they wanted the app to be available on both IOS and Android devices. 

### Pros:
* HUGE Community
* Used to make apps for FaceBook, Instagram, Discord and more
* Can make one app for IOS, Android and web instead of making one for each specific mobileOS
* Pre-built React Native specific components compile to native code by React Native toolchain
* Most popular to build apps with (right now)
* Last stable release: 03/26/2020

### Cons:
* still will have to learn React Native Specifics
* third party plugins

<img src="https://www.nativescript.org/images/default-source/logos/nativescript-logo.png?sfvrsn=2" width="500" height="100"/>

## [Native Script](nativescript.org)
NativeScript is used to build native android and IOS mobile apps. You can use a combination of Angular and NativeScript, Vue.js and NativeScript, or JavaScript/TypeScript and NativeScript. Since I'm not all that familiar with Angular or Vue.js, I will be talking about NativeScript with JS/TS for now. 

The NativeScript documentation has this handy graphic summarizing where the code lives.
<img src="https://docs.nativescript.org/img/ns-common.png">

There is a community initiative to make a hybrid of React and NativeScript. 
![And here's a table from React NativeScript creator Jamie Birch comparing React and React NativeScript.](https://d2odgkulk9w7if.cloudfront.net/images/default-source/blogs/react-ns-differences.png?sfvrsn=46850cfe_0)

### Pros
* lots of free working examples and samples with code [on NativeScript MarketPlace](https://market.nativescript.org/)
* Similar to React Native, it has pre-built components
* Can make one app for IOS, Android and web instead of making one for each specific mobileOS
* React NativeScript combines React and NativeScript
* Flexibility to choose between Angular, Vue.js or JS/TS
* Decent documentation (at first glance)

### Cons
* React NativeScript has not been fully developed (and is community developed)
* Learning curve, even using NativeScript core
* Steeper learning curve using Angular or Vue.js


<img src="https://flutter.dev/assets/flutter-lockup-c13da9c9303e26b8d5fc208d2a1fa20c1ef47eb021ecadf27046dea04c0cebf6.png" width="500" height="250"/>

## [Flutter](https://reactnative.dev/)

Flutter launched in 2017 and is Google’s UI toolkit utilizing a language called Dart. While I’ve never heard of Dart before, there is decent, well organized documentation for it. Flutter has documentation specific for developers who have experience in React and who now want to learn Flutter. 

[Here’s a fairly recent article about Flutter developers.](https://medium.com/flutter/what-are-the-important-difficult-tasks-for-flutter-devs-q1-2020-survey-results-a5ef2305429b)

According to the article the top 6 most difficult tasks were:

1. Troubleshoot platform-specific issues with my Flutter app 
2. Diagnose and fix memory issues in my Flutter app
3. Diagnose and fix CPU usage issues in my Flutter app
4. Add an existing platform-specfic native API to my Flutter app
5. Diagnosing and fixing jank UI in my Flutter app 
6. Develop a Flutter plugin (with a platform-specific implementation)



### Pros
* Used to make apps for Google, Ebay and more
* Decent Documentation
* Build Native apps for mobile, web and desktop from single codebase
* Hot Reload
* Beautiful built-in animations
* Lots of built-in widgets
* Lots of community growth
* Last stable release: 05/06/2020

### Cons 
* Smaller community than React Native
* Learning curve
* potentially harder to customize UI wise because widgets do not adapt to different platforms automatically
* potential UI troubleshooting jankness

### Recommendations
When giving a recommendation, it’s important to think about the needs of the user while also acknowledging certain technical restraints. CSExplore will most likely be accesed through a mobile device and is assumed to be an IOS/Android app. The problem with that is that users will have to download the app to access the contents if there is no mobile web version. There is also a learning curve, regardless of what framework we decide to go with (although there isn't much of one if we go with React Native).

#### Big Gamble: Flutter
As a user, I adore Google apps UI. It's simple, clean and functional (at least from the user standpoint). But trying to use Flutter is a huge gamble for our team. I'm pretty sure none of us has learned Dart so we'd all be starting at the beginning. Will it be worth it to learn about Dart and Flutter just to make a beautiful app? Having a beautiful app that's also functional can help show these students what's possible at (just) the college level and be a sort of representative of Computer Science. 

#### Play It Safe: React Native
The development team for CSExplore has experience with React so making an app with React Native shouldn't be too much of a stretch. Using React Native is less of a gamble. There's a huge community and this framework has been used to make TONS of apps already. While these apps are decent to use they're not as asthetically pleasing as apps made with Flutter. But, they are still functional and most users can't really tell (or don't care about) subtle differences.

I'd say both React Native and Flutter are strong contenders and the next step is to read more documentation and then try to build sample apps using both frameworks, and then see what kind of issues come up. 

## Readings Used

* [React Native API](https://reactnative.dev/docs/)
* [React Native Github](https://github.com/facebook/react-native)
* [NativeScript API](https://www.nativescript.org/)
* [NativeScript Github](https://github.com/NativeScript/NativeScript)
* [Flutter API](https://reactnative.dev/)
* [Flutter Github](https://github.com/flutter/flutter)
* [React Native at Airbnb](https://medium.com/airbnb-engineering/react-native-at-airbnb-f95aa460be1c)
* [React Native vs NativeScript vs Flutter](https://academind.com/learn/flutter/react-native-vs-flutter-vs-ionic-vs-nativescript-vs-pwa/)
* [Here’s a Medium article comparing React Native and NativeScript](https://medium.com/@techaffinity/react-native-vs-nativescript-7ebe0ecdc232)

