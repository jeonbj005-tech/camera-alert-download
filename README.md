# Camera Alert APK releases
## v1.3.41 — GPS 24-hour bus-lane warning

- [Download the installable APK](https://github.com/jeonbj005-tech/camera-alert-download/releases/latest/download/camera-alert-release.apk)
- [Direct versioned APK file](https://raw.githubusercontent.com/jeonbj005-tech/camera-alert-download/main/camera-alert-v1.3.41-gps-buslane-warning.apk)
- Package: `com.oemtools.cameraalert`; versionCode 69; minimum Android API 26; ARM64
- Size: 24,819,073 bytes; SHA-256: `B8DAA75930DF668CB41FEDBF60B1DADDCEC3AC5A1DE91BAD1CD545A7FA113E5B`
- Adds GPS proximity alerts for official all-day bus-lane segments. The bundled national data contains 24 segments, including 4 in Sejong. The existing small floating indicator appears within 200 m when GPS accuracy and direction checks pass, then clears after passing the segment.
- The APK signing certificate matches v1.3.40; it can update that installation in place.
- Actual Polestar GPS reception and route-level false-positive/missed-alert behavior still need vehicle verification.

Source code remains in the private `camera-alert` repository.

## v1.3.40 — bus lane popup setting

- [Download APK](https://raw.githubusercontent.com/jeonbj005-tech/camera-alert-download/main/camera-alert-v1.3.40-buslane-popup-toggle.apk)
- Package: `com.oemtools.cameraalert`; versionCode 68; minimum Android API 26; ARM64
- Size: 24,800,108 bytes
- SHA-256: `6BCB418E98D65426F753F0814EED875CB61A3A652280B22ED2BACBEA760FA37B`
- Signing certificate SHA-256: `ba8a79686fb8a03a76a8be89c292f835ef4de0d30dc5404235a98b241cc2dfa2`
- Adds the bus-lane popup visibility toggle to both the main settings and floating settings. The shared preference defaults to on, and changes apply immediately.
- Hiding this popup does not affect the speeding-camera overlay. The existing bus-lane data availability on Polestar 4 still requires an in-car check.
- The APK passes signing and alignment checks and uses the same signing key as v1.3.39, so it can update that version in place.

## v1.3.39 — bus lane overlay

- [Download APK](https://raw.githubusercontent.com/jeonbj005-tech/camera-alert-download/main/camera-alert-v1.3.39-buslane-overlay.apk)
- Package: `com.oemtools.cameraalert`; versionCode 67; minimum Android API 26; ARM64
- Size: 24,799,664 bytes
- SHA-256: `6860EF1A92542E24904912CE6A52EB4557FE3B08A64D690FE4C9E66A44849F59`
- Adds a compact, separate bus-lane status overlay and keeps the existing camera warning overlay.

## v1.3.38 — media-audio

- [Download APK](https://raw.githubusercontent.com/jeonbj005-tech/camera-alert-download/main/camera-alert-v1.3.38-media-audio.apk)
- Package: `com.oemtools.cameraalert`; versionCode 66; ARM64
- Size: 24,799,660 bytes; SHA-256: `563F366F331BB80B61680886F3AE4AC4F5629287979EE7219E2542C2C1D9D9B7`

The unversioned `camera-alert-release.apk` and `camera-alert-release.json` identify the latest release for the in-app updater.
