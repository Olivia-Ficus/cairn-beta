# Historical GitHub Release Metadata — Cairn Public Beta v1

This file preserves verification evidence for the APK that was formerly attached to the historical GitHub release `v0.1.0-public-beta.1`.

The APK is no longer distributed through GitHub, and this file is not current installation guidance. To participate in the current Cairn Beta Test, use the [Google Play testing page](https://play.google.com/apps/testing/com.cairn.launcher).

| Field | Value |
| --- | --- |
| Historical APK | `Cairn-0.1.0-public-beta-v1.apk` |
| Package | `com.cairn.launcher` |
| Version name | `0.1.0` |
| Version code | `1` |
| APK SHA-256 | `3ce05ccc4a542e924ddd588a7727766271e682398cb9e74ce7505b9ed4d471a6` |
| Signing certificate SHA-256 | `14:02:38:3A:8C:A6:72:3E:B1:5F:D0:97:A6:AB:C1:98:63:1D:F6:44:BA:8B:1B:40:3D:57:DA:84:A9:67:38:AA` |
| APK size | `13,969,440 bytes` |
| Minimum Android | `Android 8.0 (API 26)` |
| Target Android API | `35` |
| Signature verification | `One signer; APK Signature Scheme v2` |

## Historical offline validation

The exact APK requested neither `android.permission.INTERNET` nor `android.permission.ACCESS_NETWORK_STATE`. It contained no Google Play Billing, Google Data Transport, Firebase Analytics, Crashlytics, Web3Forms or remote-update implementation.

The APK included Coil's transitive OkHttp library for local image loading, but Cairn supplied only local Android content URIs to that path. The app had no network permission and no Public Beta URL/network route.

## Historical compatibility evidence

The exact APK installed and cold-launched successfully on a Pixel 7 Android Emulator running Android API 35 on `arm64-v8a`. The APK packaged its small AndroidX/DataStore native components for `arm64-v8a`, `armeabi-v7a`, `x86` and `x86_64`; runtime validation in that release phase covered `arm64-v8a`. Manufacturer-specific compatibility was not exhaustively tested.
