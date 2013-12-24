#UltraBrowser v2 for Android
#![](https://raw.github.com/thenameisnigel/Lightning-Browser/master/res/drawable-xxhdpi/ic_launcher.png)
####Download
* [Download APK from here](https://github.com/anthonycr/Lightning-Browser/blob/master/BrowserActivity.apk?raw=true)

* [Download from Amazon App Store](amazon://kindle/?dev=ryan+norris)


####Features
* Bookmarks

* History

* Multiple Search Engines (Google, Bing, Yahoo, StartPage, DuckDuckGo, etc.)

* Incognito Mode

* Flash Support

* Privacy Aware

* HOLOYOLO

####Permissions Requested and Explained

* ````INTERNET````: For accessing the web

* ````ACCESS_SUPERUSER````: Download and Flash Recoveries from COT Connector Application.

* ````BRICK````: Permission was here when I forked this project, don't know why, don't care.

* ````WRITE_EXTERNAL_STORAGE````: For downloading files from the browser

* ````READ_EXTERNAL_STORAGE````: For downloading files from the browser

* ````ACCESS_FINE_LOCATION````: For sites like Google Maps, it is disabled by default in settings and displays a pop-up asking if a site may use your location when it is enabled

* ````READ_HISTORY_BOOKMARKS````: To synchronize history and bookmarks between the stock browser and Lightning

* ````WRITE_HISTORY_BOOKMARKS````: To synchronize history and bookmarks between the stock browser and Lightning

####The Code
* Code additions are always welcome
* Please add translations/translation fixes as you see need
* Change ````FinalVariables.MAX_TABS```` from 5 to 100 to change the Lightning to the paid version
* Beware when using proguard while compiling. Some methods should not be obfuscated. Use the proguard settings file I provided for best results.
