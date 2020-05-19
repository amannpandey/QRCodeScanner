# QRCodeScanner

This is a simple QR Code Scanner Android App develope in Android Studio
Example

# Uses-Permission

For Camera Access Permission From the Phone

Add this code to the AndroidManifest.xml

<uses-permission android:name="android.permission.CAMERA"/>
<uses-feature android:name="android.hardware.camera"/>
<uses-feature android:name="android.hardware.camera.autofocus"/>

# Library

The library used in this App is ZXing ("zebra crossing") that is use for QR scanner
Sample App

The sample App is inside the sample folder
Implimenting Lib Dependencies

## Add this bellow code in the build.gradle(Module : App) file

implementation 'me.dm7.barcodescanner:zbar:1.9'
implementation 'me.dm7.barcodescanner:zxing:1.9'

implementation 'com.android.support:appcompat-v7:28.0.0'
implementation 'com.android.support:support-v4:28.0.0'

# Thank You
