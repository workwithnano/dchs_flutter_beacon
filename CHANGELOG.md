## [0.6.4]
* Added
    * New Methods:
        * setUseTrackingCache() and setMaxTrackingAge() for enhanced beacon persistence.
    * Example Updates:
        * Demonstrated the usage of setUseTrackingCache() and setMaxTrackingAge() in the example.
        * Included the usage of setScanPeriod(1000) and setBetweenScanPeriod(500) in the example.

* Updated
    * Documentation:
        * Enhanced the README to include details on the new methods.
        * Added troubleshooting tips for beacon detection issues, particularly for Android 13+.

## [0.6.3]
* Fixed bugs in the Android Beacon Scanner and improved exception handling.
* Added BlueUP beacon proximityUUID

## [0.6.2]
* Breaking changes. You have to use dchs_flutter_beacon instead of flutter_beacon.
* Rewrite plugin (Android part) with Kotlin and rename to dchs_flutter_beacon 
* Update Android-Beacon-Library to version [2.20.7]
* Update README.md with new Android permission requirement for broadcast (from Android 12)
* Recreated the example with latest flutter environment

## [0.5.1]
* Migration the example to null safety and to Android v2 embedding
* Update Android-Beacon-Library to version [2.19] with added support to Android 12 (https://github.com/AltBeacon/android-beacon-library/tree/2.19)
* Update README.md with new Android permission requirement for location (SDK 29+, Android 10, 11)

## [0.5.0]
* Migration to null safety

## [0.4.0]
* Update to Android v2 embedding
* Add broadcast Beacon feature
* Improve example app

## [0.3.0]
* Update Android-Beacon-Library to version [2.16.3](https://github.com/AltBeacon/android-beacon-library/tree/2.16.3)
* Add `BluetoothState` event channel
* Add `AuthorizationStatus` event channel [iOS only]
* Add manual check for `AuthorizationStatus`, `BluetoothState`, Location Service.
* Add opener settings for Bluetooth [Android], Location [Android] and Application [iOS].
* A lot of improvements

## [0.2.4]

* Fix bugs
* Add `close` scanning API

## [0.2.3]

* Update gradle build to latest version
* Update stop 

## [0.2.2]

* Update gradle to latest version
* Update Android-Beacon-Library to version [2.16.1](https://github.com/AltBeacon/android-beacon-library/tree/2.16.1)

## [0.2.1]

* Fix crash ranging when region not set for Android

## [0.2.0]

* Migrate to AndroidX

## [0.1.1]

* Fix region ranging for Android

## [0.1.0]

* Updating library docs
* Adding example docs

## [0.0.2]

* Adding Dart Docs

## [0.0.1]

* Initial release
* Ranging iBeacons for iOS and Android