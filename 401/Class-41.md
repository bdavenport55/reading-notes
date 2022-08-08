# Read 41

## React Native

### Getting Started with React Native<sup>1</sup>

#### 1. Name three Core Components of React Native and describe what they do.

- `<View>`: A container that supports layout with flexbox, style, some touch handling, and accessibility controls
- `<Text>`: Displays, styles, and nests strings of text and even handles touch events
- `<ScrollView>`: A generic scrolling container that can contain multiple components and views

#### 2. What problem does React Native solve (why call it native)?

Using React to build Android and iOS applications while using the app platform's native capabilities

#### 3. What are the building blocks of a React Native app? How does that compare to a React app?

- A `view` is the basic building block of RN UI: a small rectangular element on the screen which can be used to display text, images, or respond to user input. Compare to React `<div>`
- `<Text>`: compare to React `<p>`
- `<Image>`: compare to React `<img>`
- `<ScrollView>`: compare to React `<div>`
- `<TextInput>`: compare to React `<input type='text>`

### Expo<sup>2</sup>

#### 1. What solution does expo provide?

It is a framework that provides tools to help use React Native better

#### 2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.

Managed

#### 3. What is the difference between React Native and Expo?

When using a bare workflow in React Native, you could be writing directly to iOS/Android settings; Expo provides a 'shared native runtime' so you don't write native code, you only focus on writing your React App in JavaScript

### Expo Snack<sup>3</sup>

#### 1. Checkout this tool. What does snack allow you to do?

It looks like a web code editor where Expo and React Native things can be tested out

### Ejecting<sup>4</sup>

#### 1. What does “eject” mean within the context of Expo?

You can 'eject' your pure JS project from the Expo iOS/Android clients and work with native projects that can be opened and built with Xcode and Android Studio

#### 2. When should you not eject?

- You only need to distribute your app in iTunes Store/Google Play
- You are uncomfortable with writing native code
- You enjoy the painless React Native upgrades that come with Expo
- You require Expo's push notifications services
- You rely on asking for help in the Expo community

#### 3. Why might you choose to eject?

Your Expo project needs a native module that Expo doesn't currently support

### Bookmarks

- [React Native Basics](https://reactnative.dev/docs/tutorial)
- [React Native](https://reactnative.dev/)

### Footnotes

<sup>1</sup>https://reactnative.dev/docs/getting-started

<sup>2</sup>https://expo.dev/

<sup>3</sup>https://snack.expo.dev/

<sup>4</sup>https://docs.expo.dev/expokit/eject/?redirected

[Back](/reading-notes/401/401-TOC.html)