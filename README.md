# camera_demo

A simple application to demo if it is possible to capture feed from camera and play video (with sound) at the same time.

## Requirements
-  Flutter version 3.7.3
-  Flutter sdk environment: '>=2.19.2 <3.0.0'

## Getting Started
Run `flutter pub get;` to download dependencies.

Run `cd ios; pod install;` to navigate to ios folder and install pods.

Run `cd ../;` to navigate to ios folder and install pods.

Build the application by running `flutter run;`
or from the run and debug sidebar, click run icon.

### Run on device
Open 'run and debug' sidebar, click run icon.
OR
```bash
flutter run;
```
Run release
```bash
flutter run --release;
```

## Instructions.
First click the first icon at the bottom left of the screen to turn on front camera.
Then click play button (floating action button) to play the video.

Simulators & emulators do not have camera, and so this can only be tested on real devices.

Works on ios and android.
