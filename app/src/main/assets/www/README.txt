JEE TRACKER 2027 — UPDATED APP
================================

FILES
- index.html: open directly in a browser for local use.
- manifest.webmanifest, sw.js and icons/: required for installable offline-capable PWA hosting.
- This folder can be uploaded to an HTTPS static host (for example GitHub Pages).

FEATURES
- Physics, Chemistry and Mathematics chapter tracker
- Daily timetable
- Mock test marks tracker (subject scores out of 100; total out of 300)
- Study streak counter
- Editable JEE exam countdown (enter the official date when announced)
- Chapter-wise priority guide and personal confidence rating
- Mistake notebook
- Daily question targets
- Revision reminders and in-app revision widget
- Performance graph and weekly activity report
- Export/import JSON backup

PHONE INSTALLATION
1. Publish the folder contents to an HTTPS static host.
2. Open the published URL in Chrome on Android.
3. Choose Install app / Add to Home screen.
4. On desktop Chrome or Edge, use the Install icon/menu.

IMPORTANT PHONE WIDGET NOTE
The revision/countdown panel inside the app is phone-friendly, but a true Android
home-screen widget (visible without opening the app) must be supplied by a native
Android companion app. A PWA alone cannot create an Android home-screen widget.
iPhone home-screen widgets also require a native iOS app/WidgetKit extension.
The app does not claim to install a native widget.

DATA & REMINDERS
- Your data is saved in this browser/device using local storage.
- Export a backup before changing devices or clearing browser data.
- Browser notifications depend on browser/OS permission and may not run reliably
  when the PWA is fully closed. Use the in-app revision list as the reliable source.
- The JEE exam date is intentionally blank until you enter a confirmed date.
- Chapter priority labels are planning guidance, not official weightage claims.


OFFLINE VERSION NOTES
- The service worker precaches the app shell and app icons on the first successful online visit.
- After the first successful load while online, the app shell can open offline.
- Chapter, timetable, mock-test, mistake and other app records are stored in this
  browser/device using localStorage and remain available offline on that device.
- Keep using Export backup regularly. Browser storage can be cleared by the user,
  browser cleanup tools, or uninstalling/resetting the browser/app.
- Install and test the app once while online before relying on offline access.
