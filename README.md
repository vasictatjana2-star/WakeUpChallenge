# WakeUp Challenge — Android prototype v0.2

Kotlin + Jetpack Compose alarm app starter.

## Current prototype
- One daily alarm time, stored locally.
- Exact-alarm scheduling when Android permission is granted.
- Alarm receiver and foreground sound service using the device's default alarm ringtone.
- Math challenge to dismiss.
- Basic 5-minute snooze.
- Reschedule saved alarm after boot or system time changes.

## Open
1. Extract the ZIP.
2. Open this folder in Android Studio.
3. Allow Gradle sync and run on a physical Android device.

## Not production-ready yet
This remains a development prototype. Verify compilation and behavior on supported Android versions and device manufacturers. The implementation still needs:
- Robust handling for notification permission and full-screen intent permission.
- Correct notification channel/user-facing alarm controls and lifecycle edge cases.
- Multiple alarms, weekday recurrence, alarm list/edit/delete, persistent snooze state.
- More rigorous handling of reboot/timezone changes and exact alarm permission revocation.
- AdMob SDK and test ad units, consent/privacy flows, privacy policy, Google Play Data safety.
- Accessibility, localization, store graphics, signed Android App Bundle and Play Console testing.

Do not use live ad IDs during development and do not click your own ads.
Package ID is currently a placeholder: `com.example.wakeupchallenge`.
