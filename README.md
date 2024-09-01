# timer_background

A simple timer based upon the `flutter_background_service` example that starts a periodic timer that executes every second in the background.

This runs as a foreground service and shows a persistent notification while the timer is running. 

FYI - Only tested on Android at this point. Not sure if iOS works yet.

## Getting Started

 - Clone
 - `flutter run`
 - Once app is installed you will need to give it permissions. Go into the app info of the app and give it permissions manually (permission requetss are not built into this demo).
 - Kill app
 - `flutter run` 
 - View app running with notification when background service is running. 