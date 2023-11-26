## MAME4droid (0.37b5): Privacy policy

Welcome to the MAME4droid (0.37b5) Emulator app for Android!

This is an open source Android app developed by Seleuco (D.Valdeita). The source code is available on GitHub; the app is also available on Google Play.

As an avid Android user myself, I take privacy very seriously.
I know how irritating it is when apps collect your data without your knowledge.

I hereby state, to the best of my knowledge and belief, that <b>I have not programmed this app to collect any personally identifiable information</b>. All data created by the you (the user) is stored on your device only, and can be simply erased by clearing the app's data or uninstalling it.

### Explanation of permissions requested in the app

The list of permissions required by the app can be found in the `AndroidManifest.xml` file:

<br/>

| Permission | Why it is required |
| :---: | --- |
| `android.permission.VIBRATE` | Required to vibrate the device when touch control is used. Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.INTERNET` | Required to retrieve network address to host netplay games. Permission automatically granted by the system; can't be revoked by user. |
| `android.permission.READ_EXTERNAL_STORAGE` | The only two sensitive permission that the app requests, and can be revoked by the system or the user at any time. This is required to write ROMS data on external storage.|
| `android.permission.READ_EXTERNAL_STORAGE` | The only two sensitive permission that the app requests, and can be revoked by the system or the user at any time. This is required to read ROMS on external storage.|


 <hr style="border:1px solid gray">

If you find any security vulnerability that has been inadvertently caused by me, or have any question regarding how the app protectes your privacy, please send me an email or post a discussion on GitHub, and I will surely try to fix it/help you.

Yours sincerely,  
Seleuco.
seleuco.nicator@gmail.com
