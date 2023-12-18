# LocationApp

LocationApp is an Android application developed in Kotlin, leveraging Google Maps Location Services API and Jetpack Compose. The app provides a simple interface to retrieve and display the device's current location, perform reverse geocoding for address information, and handle location permissions.

## Features

- **Location Retrieval:** Utilizes Google Maps Location Services API to fetch and display the current geographical coordinates.
- **Reverse Geocoding:** Transforms coordinates into a human-readable address for user convenience.
- **Permission Handling:** Implements a straightforward permission request mechanism for location access.
- **Jetpack Compose UI:** Utilizes the modern Compose UI framework for building a clean and responsive user interface.
- **Informative Toasts:** Provides clear messages to guide users on enabling location permissions.

## Dependencies

- Google Play services location library: `com.google.android.gms:play-services-location:21.0.1`
- AndroidX Lifecycle ViewModel Compose: `androidx.lifecycle:lifecycle-viewmodel-compose:2.6.2`
- Google Play services maps library: `com.google.android.gms:play-services-maps:18.2.0`


## Usage

1. Launch the app on your Android device.
2. Press the "GetLocation" button to retrieve and display the current location.
3. Grant location permissions if prompted.
4. View the address and coordinates on the screen.

