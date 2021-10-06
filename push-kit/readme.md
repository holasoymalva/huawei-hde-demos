## Setting Up the React Native Development Environment
Set up the React Native development environment. For details, please refer to [Setting up the development environment](https://reactnative.dev/docs/environment-setup).

## Installing HMS Core (APK)

To use the APIs of Push Kit, you need to download and install HMS Core (APK) 4.0.0 or later on your device.

## Installing the Android SDK

Pay special attention to the following:

* Download Android SDK 10.0 (API level 29) and 9.0 (API level 28):
Go to Settings > Android SDK > SDK Platforms, select Android 10.0 and Android 9.0, and click OK. Android Studio will automatically download and install Android SDK 10.0 (API level 29) and 9.0 (API level 28).

* Set the environment variable ANDROID_HOME:
Open the Control Panel on the Windows, go to System and Security > System > Change settings > Advanced > Environment Variables > New, and create an ANDROID_HOME system or user variable that points to the directory to your Android SDK.

React Native requires Python 2.X, Node, and Android Studio to be installed on your computer.

## Installing Python 2.X
According to the requirements of React Native, Python 2.X must be installed.

For details about the installation and configuration methods, please refer to documents on the official Python website.

## Installing Node.js
For details about the installation and configuration methods, please visit the official Node website.

# Integrating React Native Push Plugin

## Perform the following steps:

* Open the build.gradle file in the android directory of your React Native project.
  * Go to buildscript and configure the Maven repository address and AppGallery Connect plugin for the HMS SDK.
