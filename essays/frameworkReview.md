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

To this day I’ve only used React to make web apps. I have limited brainspace so I’d rather just stick with what I know about React (which isn’t much). But technology is always changing so maybe there’s something new out there worth learning.

First, here’s a quick run down of React Native.


![](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii0xMS41IC0xMC4yMzE3NCAyMyAyMC40NjM0OCI+CiAgPHRpdGxlPlJlYWN0IExvZ288L3RpdGxlPgogIDxjaXJjbGUgY3g9IjAiIGN5PSIwIiByPSIyLjA1IiBmaWxsPSIjNjFkYWZiIi8+CiAgPGcgc3Ryb2tlPSIjNjFkYWZiIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIi8+CiAgICA8ZWxsaXBzZSByeD0iMTEiIHJ5PSI0LjIiIHRyYW5zZm9ybT0icm90YXRlKDYwKSIvPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIiB0cmFuc2Zvcm09InJvdGF0ZSgxMjApIi8+CiAgPC9nPgo8L3N2Zz4K | =300x300)

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

## [Native Script](nativescript.org)
NativeScript is used to build native android and IOS mobile apps. You can use a combination of Angular and NativeScript, Vue.js and NativeScript, or JavaScript/TypeScript and NativeScript. 

I tried out a sample from NativeScript’s website but it required me to download 2 different mobile apps, NativeScript Preview and NativeScript Playground. 


![And here's a table from React NativeScript creator Jamie Birch comparing React and React NativeScript.](https://d2odgkulk9w7if.cloudfront.net/images/default-source/blogs/react-ns-differences.png?sfvrsn=46850cfe_0)

### Pros

### Cons
* React NativeScript has not been fully developed

## [Flutter](https://reactnative.dev/)

Flutter is Google’s UI toolkit and it uses a language called Dart. While I’ve never heard of Dart before, there is decent, well organized documentation for it. Flutter has documentation specific for developers who have experience in React and who now want to learn Flutter. 


[Here’s a fairly recent article about Flutter developers.](https://medium.com/flutter/what-are-the-important-difficult-tasks-for-flutter-devs-q1-2020-survey-results-a5ef2305429b)

### Pros
* Used to make apps for Google, Ebay and more
* Decent Documentation
* Quinne loves Google UIs

### Cons 
* Smaller community than React Native
* Learning curve

### Recommendations

| Framework | Pros | Cons | 
| React | | | 
| NativeScript | | | 
| Flutter |  * Really good documentation for Flutter and Dart * Special section to transition React Developers *Made and used by Google, a FANG company and could give valuable experience | The whole team would have to learn a new language and framework | 

When giving a recommendation, it’s important to think about the needs of the user while also acknowledging certain technical restraints. CSExplore will most likely be accesed through a mobile device and is assumed to be an IOS/Android app. The problem with that is that user’s will have to download the app to access the contents. 

#### Recommendation Performance and UI: Flutter
As a user, I adore Google apps UI. It's simple, clean and functional (at least from the user standpoint). 


### Recommendation Fast Production Time and Compatibility with RadGrad2: React Native
The development team for CSExplore has experience with React so making an app with React Native shouldn't be too much of a stretch. 


## Articles and APIs

* [React Native vs NativeScript vs Flutter](https://academind.com/learn/flutter/react-native-vs-flutter-vs-ionic-vs-nativescript-vs-pwa/)
* [Here’s a Medium article comparing React Native and NativeScript](https://medium.com/@techaffinity/react-native-vs-nativescript-7ebe0ecdc232)

