# Conviva Android: "Reference App" + "Documentation" Project
Welcome to the Conviva Android Sensor Integration!

For the integration instriuctions please go to:
https://github.com/konstantin-shinkarenko/doc-sample-proj/wiki


Reference Application is designed and developed to ease the integration of Conviva analytics in to streaming applications with less effort. This application is designed similar to customer applications to easily correlate with the customer app features. It is a project with detailed code snippets on how to integrate Conviva analytics.

Supported platforms: 
```
  Android 4.4 and above
```

Players & SDKs integrated: 

  ExoPlayer
  NexPlayer
  Freewheel SDK
  Google Ad SDK

Reference App follows hybrid architecture with two main layers as below:

  UI layer (conviva-react-native-refapp): This layer is developed using cross platform React Native framework.
  Responsibilities of this layer includes:
    UI Rendering
    Configuration setup
    Content listing
  Native layer (Native): This layer is developed using native platform (Android/Java).
  Responsibilities of this layer includes:
    Video player functionality (playback of content)
    Conviva Integration

  


