# Azadari Connect — Android Starter

This is the first Android UI prototype for the worldwide Majalis/Kafla platform.

## Included
- Home screen
- Majalis list
- Kafla list
- Donation screen
- Tando Muhammad Khan as the initial featured city
- Package/application ID: `com.azadariconnect.app`

## Next production integrations
1. Firebase Authentication + Firestore
2. Firebase Realtime Database for live kafla location
3. Google Maps SDK / Maps Compose
4. Android foreground location service for organizer live tracking
5. Verified organizer/admin panel
6. Pakistan payment gateway integration (JazzCash/Easypaisa/bank workflow subject to provider APIs)
7. Push notifications
8. Privacy policy, terms, reporting and moderation
9. Production signing and Play Console release

## Build
Open this folder in Android Studio. Let Gradle sync, then run the `app` configuration on an Android device/emulator.

Before publishing, update compile/target SDK and all dependencies to the current Google Play requirements, create a release signing key, test thoroughly, and build an Android App Bundle (AAB).
