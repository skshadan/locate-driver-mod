# Locate driver
An Open Source Android Application that automatically shares your location while you drive based on SMS. 

All you have to do is to choose a destination, a keyword and to start the application. When someone sends you an SMS with that keyword, the application will auto respond with your location and ETA to your destination.

The application it is battery friendly because it uses a "BroadcastReceiver", which means that the application is not running on the background,. The Android system sends an event when a SMS is received and the application will start in the background. It uses the GPS for a limited time, only to get the location for the response, after that it will close again.

# Download
Play store: https://play.google.com/store/apps/details?id=com.micutu.locatedriver

Github: https://github.com/micku7zu/Locate-driver/releases

# Screenshots
<img src="http://i.imgur.com/PoqOmM2.png" width="400">
<img src="http://i.imgur.com/c7R7tZN.png" width="400">
<img src="http://i.imgur.com/pNenn0U.png" width="400">
<img src="http://i.imgur.com/dRtUsJb.png" width="400">

# Demo youtube video
[![Demo](http://img.youtube.com/vi/liXTWxGoO9E/0.jpg)](http://www.youtube.com/watch?v=liXTWxGoO9E)

# Libraries used
Smart location lib created by Nacho Lopez (mrmans0n): https://github.com/mrmans0n/smart-location-lib

# License
This work is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
