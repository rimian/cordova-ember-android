# Cordova Ember Android

This is a basic Ember.js hello world install on Cordova using Android plugin. If it all works properly, you should be able to start up an Android emulator.

## Prerequisites

- [cordova](https://www.npmjs.org/package/cordova)
- [Android SDK](https://developer.android.com/studio/index.html)
- [ember-cli](http://www.ember-cli.com)
- [ember-cli-cordova](https://github.com/poetic/ember-cli-cordova)

## Supported Platforms

This guide is mainly for Android but it should work for iOS.

## Installation

```
git clone https://github.com/rimian/cordova-ember-android.git
cd cordova-ember-android
npm install
```

The documentation at [ember-cli-cordova](https://github.com/poetic/ember-cli-cordova/blob/master/docs/getting-started.md) says you can set the platform in config but that doesn't seem to work. To install and build for Android, you'll need to pass the `--platform=android` flag in to your commands.

To run a build run

```
ember cordova:build --platform=android
```
