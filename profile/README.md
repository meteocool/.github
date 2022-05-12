# meteocool

[meteocool](https://meteocool.com/) provides free & open-source
real-time rain radar and storm tracking functionality for iOS,
Android and the web. Currently available in Central Europe (DWD).
Use it to both chase or avoid upcoming weather - that's up to you.

![An exemplary cloud formation with high reflectivity (aka thunderstorm)](https://raw.githubusercontent.com/v4lli/meteocool/master/doc/pano-thunderstorm.jpg "An exemplary cloud formation with high reflectivity")

meteocool currently uses radar data provided by DWD, realtime lightning
information from the awesome blitzortung.org project and satellite imagery from Copernicus.


<a href="https://itunes.apple.com/de/app/meteocool-rain-radar/id1438364623"><img src="https://raw.githubusercontent.com/v4lli/meteocool/master/frontend/assets/download-on-appstore.png" style="width 32%; float: left;" alt="Download on Apple Appstore"></a>
<a href="https://play.google.com/store/apps/details?id=com.meteocool"><img src="https://user-images.githubusercontent.com/1577223/57536457-84883480-7344-11e9-899d-c31ac124917c.png" style="width: 31%" alt="Download on Google Play Store"></a>
<a href="https://f-droid.org/de/packages/com.meteocool/"><img src="https://raw.githubusercontent.com/meteocool/core/develop/public/assets/fdroid-small.png" style="width: 29%" alt="Get it on F-Droid"></a>


## Features

<img src="https://raw.githubusercontent.com/v4lli/meteocool/master/doc/ios-lockscreen.png" alt="iOS Notifications" width="50%" align="right">

* **Automatic Map Updates:** the biggest inconvenience with most weather radar
  visualisations is out-of-date data. meteocool always transparently shows the
  latest available data without any interaction.  Say goodbye to hammering F5!
* **Live Lightning Strikes:** new lightning strikes are displayed instantly,
  giving you an even better feeling for the cloud formation's intensity,
  trajectory and speed. Based on data from blitzortung.org.
* **iOS & Android Apps:** "native" iOS and Android apps provide battery-efficient
  background location services to allow for accurate rain notifications
  & navigation.
* **Push Notifications:** get notified about incoming rain up to 60 minutes
  in advance. Requires iOS or Android App (currently not available on F-Droid).
  
* Automatic **Dark Mode:** great for HUD-like displays and general
  night time usage. Turns on automatically if you enable dark mode
  on your iOS, Android or desktop system (where supported).

* **Progressive Web App:** responsive, connectivity independent and
  app-like on modern browsers. Requires WebGL.

<img width="100%" alt="Screenshot 2019-05-11 13 33 19" src="https://user-images.githubusercontent.com/1577223/57573080-444bb380-7423-11e9-935d-2a990f5026f6.png">
## Contributing

We welcome contributions of all kinds. Check out the [Frequently Asked Questions](https://github.com/meteocool/core/wiki/FAQ) (currently only available in German).

## Acknowledgements

All our code & documentation is licensed under the AGPL-3.0 license unless noted otherwise in the respective repository's `COPYRIGHT.md` file.

meteocool is developed and maintained by [Valentin Dornauer](https://github.com/v4lli), servers are paid for by [Jonas](https://github.com/pew); Special thanks to [OroraTech](https://github.com/ororatech) for their continued sponsorship.
