# Location Detector

Location Detection in Flutter

## Adding the Geolocator plugin

### 1. pubspec.yaml
<code>dependencies:
  flutter:
    sdk: flutter
  geolocator: ^5.1.3
</code>
### 2. Add the following to your "gradle.properties" file:
android.useAndroidX=true
android.enableJetifier=true

### 3. Make sure you set the compileSdkVersion in your "android/app/build.gradle" file to 28

### 4. For android, head on over to your AndroidManifest.xml and add either of these permissions:
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />

