# Conviva Android: "Reference App" + "Documentation" Project
Welcome to the Conviva Android Sensor Integration!

For the integration instriuctions please go to: [Conviva Android Documentation Wiki](https://github.com/konstantin-shinkarenko/doc-sample-proj/wiki)


Reference Application is designed and developed to ease the integration of Conviva analytics in to streaming applications with less effort. This application is designed similar to customer applications to easily correlate with the customer app features. It is a project with detailed code snippets on how to integrate Conviva analytics.

Supported platforms: 
```
  Android 4.4 and above
```

Players & SDKs integrated: 
```
  ExoPlayer
  NexPlayer
  Freewheel SDK
  Google Ad SDK
```
Reference App follows hybrid architecture with two main layers as below:
```
  UI layer (conviva-react-native-refapp): This layer is developed using cross platform React Native framework.
  Responsibilities of this layer includes:
    UI Rendering
    Configuration setup
    Content listing
  Native layer (Native): This layer is developed using native platform (Android/Java).
  Responsibilities of this layer includes:
    Video player functionality (playback of content)
    Conviva Integration
```
Getting Started

Prerequisites:
```
Laptop/Desktop running with Mac/Ubuntu/Windows OS

Android Studio

Github account
    Access to https://github.com/Conviva/
    Read access to below repos
        https://github.com/Conviva/conviva-android-reference-app
        https://github.com/Conviva/conviva-react-native-refapp
        
    Setup ssh keys in github to checkout the code seamlessly.
        How to setup? - Setup Guide
```              
For development & testing:
```
git clone git@github.com:Conviva/conviva-android-reference-app.git
cd conviva-android-reference-app/
run the below scripts
    sh evnSetup.sh (if npm is not already installed)
    sh projSetup.sh
```

Setup Guide:
```
This project requires command line tools - npm,react native cli and Android Studio to be installed on development machine.
```

Projects & Submodules:
```
Conviva-android-reference-app:-  This is the project repo for android reference.
Native:- This folder cotains the android bridge for react native.
Submodule:
    conviva-react-native-refapp:- This project contains UI layer written using cross platform React native framework.
```
Installation:
```
In order to install application,
Connect Android phone/emulator/firetv
Build & Run the application using Android Studio.
```

Conviva Integration classes:
```
    CVABaseEIIntegrationRef.java & ExoPlayerEventListener.java: illustrates main content integration using ExoPlayer as a reference.

    CVABaseAIIntegrationRef.java & GoogleIma.java: source code illustrating integration of Ad events using Google IMA SDK as a reference.

   ??? CVABaseCIIntegrationRef.java: These files contain code for handling Conviva Content Insights integration. We are recommending to include these files in your project and modify only if needed. ???
```
Built With
```
JavaScript (React Native)
Android
Java
```

