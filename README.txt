U-MART Android wrapper project

This packages the existing U-MART HTML prototype inside an Android WebView.
It preserves the current demo behavior (including browser/local storage).

Important: the current HTML prototype does NOT actually use Firebase/Firestore;
it stores cart/orders in localStorage. Firebase rules alone do not connect it.

Build with Android Studio or AndroidIDE. Use Build > Build APK(s).
Application ID: com.umart.app
