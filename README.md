# PriceFlow

Arabic/English responsive PWA price calculator. Paste price columns, apply 10%, 15%, 25% or custom percentage, always round up, copy a plain numeric column, and retain the latest 50 copied operations locally.

## GitHub Pages
Go to Settings > Pages > Build and deployment > Deploy from a branch, select main / (root), and Save. URL: https://bakerer122-dotcom.github.io/PriceFlow/

## Google sign-in / cloud sync (NOT configured yet)
Create a Firebase project and Web app in https://console.firebase.google.com. Enable Authentication > Google, create Cloud Firestore, apply firestore.rules, and add bakerer122-dotcom.github.io under Authentication > Settings > Authorized domains. Paste the public Web app config object into firebase-config.js in place of null. Never publish a service account private key.

The SVG app icon is a provisional drawing. The original user-supplied JPEG and PNG PWA icons are in the previously prepared PriceFlow ZIP; upload those assets to preserve the exact supplied illustration, then update icon links if necessary.

For offline use, open the deployed site online once; clipboard read needs supported browser permissions.