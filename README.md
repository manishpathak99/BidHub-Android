# FlappyBid: Android App
Android client for HubSpot's open-source silent auction app. For an overview of the auction app project, [check out our blog post about it](http://dev.hubspot.com/coming-soon)!

![](http://i.imgur.com/qIud2uSl.png)

## Getting started
If you haven't yet, you're going to want to set up Parse by following the instructions in the [FlappyBid-CloudCode repo](https://github.com/HubSpot/FlappyBid-CloudCode). All set? `git clone` this repository and import it into Android Studio. Grab your application ID and client key from Parse (Parse > Settings > Keys). Set `APP_ID` and `CLIENT_KEY` in *AuctionApplication.java* to these values. Then just run the app, enter your name and email address, and you should see Test Object 7! Bid on it and see what happens.

##Customization
Here's a list of the HubSpot-specific assets in the app, which you can change to whatever you want:
* `drawable/notificationicon.png` status bar icon for push notifications
* `drawable/appicon.png` app icon for the app drawer and for push notifications
* `drawable/bg.png` background for the login screen and for the hamburger menu
