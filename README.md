# Location Detector

Location Detection in Flutter

## Adding the Geolocator plugin

### 1. pubspec.yaml
dependencies:
  flutter:
    sdk: flutter
  geolocator: ^5.1.3

### 2. Add the following to your "gradle.properties" file:
android.useAndroidX=true
android.enableJetifier=true

### 3. Make sure you set the compileSdkVersion in your "android/app/build.gradle" file to 28

### 4. For android, head on over to your AndroidManifest.xml and add either of these permissions:
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />

### 5. Starting with iOS and the Info.plist, add the following key/value pairs and customize them to your liking:
<key>NSLocationWhenInUseUsageDescription</key>
<string>This app needs access to location when open.</string>

<key>NSLocationAlwaysUsageDescription</key>
<string>This app needs access to location when in the background.</string>

<key>NSLocationAlwaysAndWhenInUseUsageDescription</key>
<string>This app needs access to location when open and in the background.</string>
