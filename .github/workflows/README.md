# RIDAA Store Android

Android app wrapper for the live RIDAA Store website.

## Live site
https://ridaa-store.almshagbaabdallah.workers.dev

## What is included
- Same live store UI/content as the website
- Supabase-backed products/settings/admin stay synchronized with the website
- Admin file upload support from inside Android WebView
- Browser back navigation
- External handling for WhatsApp, telephone, email and other external links
- Offline error screen
- Native splash/status/navigation colors matching RIDAA
- GitHub Actions workflow that builds an APK automatically

## Build APK using GitHub (easiest)
1. Create a new GitHub repository, for example `RIDAA-Store-Android`.
2. Upload the CONTENTS of this folder to the repository root.
3. Open the repository's **Actions** tab.
4. Open **Build RIDAA APK** and run it, or wait for the automatic run after pushing to `main`.
5. When the run finishes, download the artifact named **RIDAA-Store-APK**.
6. Extract the artifact ZIP; inside is `app-debug.apk`.

## Build with Android Studio
Open this folder as an Android Studio project, allow Gradle/SDK sync, then use:
Build > Build APK(s)

Package id: `com.ridaastore.app`
App name: `RIDAA Store`
