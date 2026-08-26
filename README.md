# Android Testing: Espresso + UIAutomator Lab

A deliberately small counter app with two instrumentation layers:
- **Espresso** verifies behavior inside the app (`Increment` changes `0` to `1`).
- **UIAutomator** demonstrates system/cross-app interaction by navigating to the launcher.

CI compiles both the debug APK and the AndroidTest APK. Instrumented execution requires an emulator/device.
