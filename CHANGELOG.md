1.9 (Unreleased)
==

- Updated targetSDK to 34 (Android 14) with compatibility fixes.
- More reliable delayed freezing using AlarmManager (thanks parmaster84).
- Support for cross-profile interactions allowlisting (e.g. for Gboard).
- Removed "Fake Camera" feature as it has not been supported since R.
- Version displayed within the app has now been changed to also reflect the exact Git commit when the app is built.
- File Shuttle no longer appends ".null" or ".bin" suffixes unnecessarily. This should make it work much better with file managers such as Material Files.
- File Shuttle now triggers media scanning much more robustly. Media files (pictures, videos, etc.) copied into the work profile should now show up much quicker in gallery apps.

1.8
===

- Updated targetSDK to 33 (Android 13) with compatibility fixes.
- UI style revamp with Material You support on Android 12+.

1.7
===

- Revamped the initial setup process to include a full setup guide for better clarity and less confusion.
- Upgraded targetSDK to 31 (Android 12) with compatibility fixes.
- Upgraded dependencies.
- Translation updates thanks to our wonderful community.

1.6
===

- Start of in-repo changelogs
- Add support for Android 11 (c147377, 3852bd, and more) (__Note__: For now, File Shuttle is not available in the version on Google Play due to policy reasons, as they will not be allowing apps with All Files permission before 2021.)
- Shelter can no longer be installed to external storage (removable SD cards) (9a6777 by Camilio Alejo)
- Allow more browsable intents to be passed across work / main profile boundary (43444b by Camilio Alejo)
- A new shortcut to Documents UI is available in the three-dot menu of Shelter, because on Pixels the Google Files app may not be able to open File Shuttle correctly (a121ee)
- You can now choose to block or allow cross-profile contact access via a settings option (749ad1)
- Thanks to translators participating in our Weblate instance (https://weblate.typeblog.net), Shelter is now available in more languages. You can now contribute translations easier than ever by using the Weblate interface.
