---
title: "Controller"
excerpt: "Mobile application to control ESP based microcontroller device"
header:
  image: /assets/images/app_icon/logo_controller.png
  teaser: /assets/images/app_icon/logo_controller.png
tags:
  - Flutter
  - ESP
  - Mobile Application
sidebar:
  - title: "Role"
    image: 
    image_alt: "logo"
    text: "Programmer"
  - title: "Skills"
    text: "Firmware programming, Application development, C/C++, Flutter"

gallery_controller:
    -   image_path: /assets/images/controller/controller_home.png
    -   image_path: /assets/images/controller/controller_connection.png
    -   image_path: /assets/images/controller/controller_joystick.png

---

## Notable Features

+ WebSocket Connection
+ Auto discovery using mDNS
+ Developed with Flutter framework using Dart

## Summary

Controller is the first mobile app i have ever developed after completing tutorials on Dart and Flutter programming. The requirement of this app was to be able to control ESP based microcontroller remotely using mobile phone. This app should also be compatible with both version of ESP, ESP8266 and ESP32.

There are two main components of this project, the mobile app development using Dart and Flutter framework, and the library development using C/C++ for the microcontroller. To be able to use this app, user would need to use the library written specifically for communication with the Controller app.

Source control with Git has been applied while working in this project. This to ensure that i would always be able to go back to the previous version, in case bugs are discovered.

[Play Store Listing](https://play.google.com/store/apps/details?id=com.invokcontroller.app)  
[GitHub Project Page](https://github.com/invoklab/InvokController)

{% include gallery id="gallery_controller"%}
