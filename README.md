# Android Support Library v4

revision 24.1.1, `971884 bytes`

## Contents

This package contains the latest `android-support-v4.jar` file from Android SDK.

- https://developer.android.com/topic/libraries/support-library/features.html#v4
- https://developer.android.com/reference/android/support/v4/app/package-summary.html

## Install

```
cordova plugin add cordova-plugin-android-support-v4-jar
```

## How to upgrade

Upgrade Android SDK support library

- start Android SDK Manager with running command `android`
- check item `Extras` / `Android Support Library`
- upgrade if available
- write down the latest revision number

If the revision number is greater than the jar file of this plugin, it is upgradeable.

Check file size and overwrite the jar file to the plugin library

```
ls -l /usr/local/var/lib/android-sdk/extras/android/support/v4/android-support-v4.jar
copy /usr/local/var/lib/android-sdk/extras/android/support/v4/android-support-v4.jar .
```

Modify the version number of `plugin.xml` and save.
