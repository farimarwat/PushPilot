# PushPilot
Introducing PushPilot: the ultimate Android library that eliminates the headache of implementing Google Cloud Messaging (GCM) in your app. With PushPilot, you can integrate GCM with just one simple step, saving your time and effort. Say goodbye to complex setups and hello to seamless push notification integration with PushPilot.

## Step 1:
<a href="https://firebase.google.com/docs/android/setup">Add firebase</a> to your project by following the google steps

## Step 2:
Implement PushPilot:
```
implementation "io.github.farimarwat:pushpilot:1.0"
```
## Final Step:
Done

## Testing
Run the app and get the token from android studio log by filtering "GCM Token"

<img src="https://github.com/farimarwat/PushPilot/blob/main/gcm_tokken.png" />

Go to firebase console, Engage>Messaging>Cloud Messaging and send a test message using this token.

**Note:Some time you may receive the push message very late. Its google problem not the library**
