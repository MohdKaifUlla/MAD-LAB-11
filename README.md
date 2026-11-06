# Experiment 11 – Display a Map Using Google Maps API

## Student Information

- **Name:** Mohammed Kaif Ulla
- **USN:** 25MCAR0226
- **Subject:** Mobile Application Development (MAD)
- **Experiment No.:** 11

## Aim

To develop an Android application that displays an interactive Google Map and shows the user's current location using location services.

## Description

This Android application demonstrates the integration of Google Maps SDK into an Android application using Kotlin and XML.

The application displays Google Maps using SupportMapFragment and requests location permissions from the user.

After permission is granted, FusedLocationProviderClient retrieves the last known location of the device. The application enables the My Location feature and moves the map camera to the retrieved location.

## Technologies Used

- Android Studio
- Kotlin
- XML
- Android SDK
- Google Maps SDK
- Google Play Services Location API
- FusedLocationProviderClient
- Material Design
- ConstraintLayout

## Features

- Displays an interactive Google Map.
- Requests location permissions at runtime.
- Displays the user's location when available.
- Provides map zoom controls.
- Moves the map camera to the user's location.
- Displays student name and USN.
- Handles permission denial.

## Permissions Used

```xml
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION" />
```

## Working Procedure

1. Launch the Android application.
2. Google Maps loads using SupportMapFragment.
3. The application checks location permissions.
4. If permissions are not granted, it requests permission.
5. After permission is granted, the application enables My Location.
6. FusedLocationProviderClient retrieves the last known location.
7. The map camera moves to the retrieved location.
8. The user's location is displayed on Google Maps.

## Output Screenshots
<img width="1536" height="1024" alt="Triptych Map Screenshots with Updated Details" src="https://github.com/user-attachments/assets/a475cb55-3e03-4481-a930-7bda4a24f0ff" />


## Default Map Location

- **Latitude:** 28.6139
- **Longitude:** 77.2090
- **Location:** New Delhi

## Map Zoom Level

The application uses a zoom level of 15 when moving the camera to the retrieved device location.

## API Key Configuration

Google Maps requires a valid API Key configured in AndroidManifest.xml. The Google Maps SDK must be enabled in Google Cloud Console.

## Learning Outcomes

- Understanding Google Maps SDK.
- Integrating Google Maps into Android applications.
- Understanding GPS and geographical coordinates.
- Implementing runtime location permissions.
- Using FusedLocationProviderClient.
- Understanding SupportMapFragment.
- Controlling map camera and zoom functionality.

## Result

The Android application was successfully developed to display Google Maps and retrieve the device's last known location using FusedLocationProviderClient.

## Conclusion

This experiment helped in understanding Google Maps integration in Android applications. It also demonstrated location permission handling, retrieving device location, and controlling map camera movement.

---

**Developed By:** Mohammed Kaif Ulla  
**USN:** 25MCAR0226
