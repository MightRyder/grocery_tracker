Grocery Price Tracker — PWA files

Files in this ZIP:
- manifest.webmanifest
- icon-192.png
- icon-512.png

How to use:
1) Place ALL files next to your index.html (same folder).
2) In <head> of index.html, add:
   <link rel="manifest" href="/manifest.webmanifest">
3) Deploy to any HTTPS host (Firebase Hosting recommended).

Firebase Hosting quick-start:
npm i -g firebase-tools
firebase login
firebase init hosting   # choose your Firebase project, set public dir to the folder containing index.html
firebase deploy

Then open https://<your-site>.web.app on Android Chrome → ⋮ → Add to Home screen.