# Google Maps Integration

## Overview

This Flutter application demonstrates how to integrate Google Maps into a Flutter app and place a marker on Cairo, Egypt. The app features a page with a Google Map, displaying a red marker at the specified location.

## What the Code Does

- **Google Maps Display**: The app shows a Google Map on the screen with a title in the AppBar.
- **Marker on Cairo**: A red marker is placed on the map at the coordinates for Cairo, Egypt.

## How the Code Works

1. **Imports**:
   - The app imports necessary packages: `dart:async` for asynchronous programming, `flutter/material.dart` for UI components, `geolocator` for location services, and `google_maps_flutter` for Google Maps functionality.

2. **State Management**:
   - The main widget is a `StatefulWidget` that maintains the state of the map and markers.

3. **UI Structure**:
   - The UI consists of an `AppBar` with the title "Google Maps" and a `GoogleMap` widget that displays the map.
   - The `GoogleMap` is initialized with a camera position targeting Cairo, Egypt.

4. **Marker Placement**:
   - A marker is added to the map at the coordinates for Cairo (30.0444° N, 31.2357° E) in the `_determinePosition` method.

5. **Location Permissions**:
   - The app checks for location permissions and handles user permissions appropriately.

6. **Loading Indicator**:
   - A `CircularProgressIndicator` is displayed while the map is loading.

## Used Packages

1. **google_maps_flutter**
   - **Description**: A Flutter plugin for integrating Google Maps in a Flutter application.
   - **Link**: [google_maps_flutter](https://pub.dev/packages/google_maps_flutter)

2. **geolocator**
   - **Description**: A Flutter plugin for accessing the device's location services.
   - **Link**: [geolocator](https://pub.dev/packages/geolocator)
