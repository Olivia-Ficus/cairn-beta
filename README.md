# Cairn Public Beta v1

Cairn is an Android launcher that adds an intentional pause before selected apps opened through the Cairn launcher experience. The Free plan lets you use the pause with one app.

## Why sideload?

This Public Beta is distributed directly while Google Play purchasing is not available for the beta. Sideloading lets you install the APK without changing Cairn's long-term package or signing identity.

Only install an APK whose SHA-256 and signing-certificate fingerprint match the values in `RELEASE_METADATA.md`.

## Install

1. Use Android 8.0 or newer.
2. Download `Cairn-0.1.0-public-beta-v1.apk` from the corresponding canonical Cairn Release.
3. If Android asks, allow your browser or file manager to install unknown apps.
4. Open the downloaded APK and approve installation.
5. Launch Cairn and complete onboarding.
6. When prompted, choose Cairn as your Home app. You can also change the default Home app later in Android Settings.

## Cairn plans

Cairn is free to use with a pause on one app. Pro lets you bring the same pause to as many apps as you choose.

Purchases aren't available during Public Beta. These are the plans Cairn will offer through Google Play:

- Free — One app
- Monthly — $7.99 / month
- Yearly — $69 / year
- Lifetime — $149 once

The Public Beta has no checkout, waitlist, Trial or substitute payment flow.

## Offline and privacy

Cairn Public Beta v1 does not connect to the internet or send usage data off your device.

Launcher settings, selected apps, Future Notes and River Report history stay on the device. The app does not include analytics, crash telemetry or remote update checking.

## Launcher boundary

Cairn's intentional pause belongs to the Cairn launcher experience. It applies primarily when an app is opened through Cairn Home or Cairn's launcher surfaces. Launches from Recent apps, notifications, another launcher or other Android system paths can bypass Cairn. Cairn is not a system-wide app blocker.

## Updates

Public Beta v1 does not automatically check for or install updates. Return to the canonical Cairn Releases surface manually to check for a newer version.

A compatible update uses the same package and signing identity, so Android can install it over the existing Cairn app. Verify the new release metadata before installing it.

## Known limitations

- Google Play purchasing is not available in this beta.
- The intentional pause does not cover every Android app-launch path.
- Automatic update discovery is not included.
- Android compatibility was validated on the stated test environment, not exhaustively across every manufacturer or device configuration.

## Support and feedback

Email `hello.cairn@proton.me`.
