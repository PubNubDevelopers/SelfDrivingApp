## Please note that this project is no longer actively maintained or accepting Pull Requests.  Please use the [Delivery Application](https://github.com/PubNubDevelopers/delivery-demo) instead.

----------------------------

# Self Driving Car App


# Quickstart

1. In order to set up PubNub in your android app, you will need to create a PubNub app in the PubNub Admin Dashboard (it’s free). Upon creating the app, you will be assigned a subscribe key and publish key. You will need to go to the Constants.java class and enter these credentials where it says INSERT_SUBSCRIBE_KEY and INSERT_PUBLISH_KEY respectively.

2. Now, we must set up our Google Maps API key, so that we can use it in our application. In order to do this head over to Google’s Developer API console. Here, we will create a new project and then generate an API key. Once you have the API Key, enter it in the Android Manifest file, where it says INSERT_API_KEY.

3. Ensure that you have downloaded Google Play Services in your Android SDK Manager, accessible from the tool bar at the top of Android Studio. 

# Required Gradle Dependencies

``` 
implementation group: 'com.pubnub', name: 'pubnub-gson', version: '4.12.0'

implementation 'com.google.android.gms:play-services-maps:15.0.1'

implementation "com.google.android.gms:play-services-location:15.0.1"

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-core', version: '2.9.2'

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-annotations', version: '2.9.2'

implementation group: 'com.fasterxml.jackson.core', name: 'jackson-databind', version: '2.9.2'
```

# Required Manifest Permissions

``` xml
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
```

**Sign up for PubNub click here:**

<a href="https://dashboard.pubnub.com/signup?devrel_gh=RealtimeTaxiAndroidDemo">
    <img alt="PubNub Signup" src="https://i.imgur.com/og5DDjf.png" width=260 height=97/>
</a>

