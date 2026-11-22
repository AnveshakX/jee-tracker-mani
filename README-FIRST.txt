JEE TRACKER 2027 — ANDROID APK PROJECT

This project wraps the supplied HTML tracker inside an Android WebView and bundles
all web files locally in the APK. It does not load the Netlify website at runtime.
The tracker uses localStorage for its data, with WebView DOM storage enabled.

BUILD THE APK USING GITHUB ACTIONS (NO ANDROID STUDIO):
1. Create a new empty repository at https://github.com/new
2. Upload the CONTENTS of this folder (not the outer folder) to the repository.
3. Commit the files to the main branch.
4. Open the repository's Actions tab.
5. Open "Build JEE Tracker APK". If it has not started automatically, choose
   Run workflow.
6. Wait for the workflow to finish successfully.
7. Open the completed workflow run, scroll to Artifacts, and download
   "JEE-Tracker-2027-APK".
8. Extract the downloaded artifact ZIP. It contains app-debug.apk.
9. Transfer app-debug.apk to the Android phone and install it.

NOTES:
- This is an installable Android APK with the app's HTML bundled locally.
  It does not depend on Netlify to load the app.
- Study records are stored locally in this app's WebView storage. They are not
  automatically synced to the website or other devices.
- Use the app's own Export backup feature before uninstalling or clearing data.
- This debug APK is suitable for personal installation/testing. For public
  Play Store release, create a separately signed release build and keep its key.
- Android 6.0+ is targeted (minSdk 23); Android may ask permission to install
  apps from the file manager/browser used to open the APK.
