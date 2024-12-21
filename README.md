# Expo Linking.getInitialURL() Android Inconsistency

This repository demonstrates a bug in Expo's `Linking` API on Android. The `getInitialURL()` method sometimes returns `null` even when the app is launched from a deep link, causing unreliable deep link handling.  The solution provided mitigates this by adding error handling and fallback mechanisms.