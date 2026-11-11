# FORGE iPhone app (installable web app)

## What it does
- Daily calorie and macro totals
- Manual food entry and food diary
- Camera barcode scanning using html5-qrcode
- Product lookup through Open Food Facts
- Daily water tracking
- Weight history
- Saves data in the browser on this device using localStorage

## Important limitations
- This is an installable web app (PWA), not a native App Store app.
- It must be hosted on an HTTPS website for iPhone camera access and home-screen installation.
- Barcode lookup requires internet and depends on the product being present in Open Food Facts.
- Product nutrition is shown per 100 g when supplied; change values to match the amount eaten before adding.
- Data is stored locally in this browser. Clearing website data or changing browsers/devices can remove it. There is no cloud sync or account backup.
- Starter nutrition targets are examples. Set your own goals in the app.

## Publish and install
1. Upload all files in this folder to a static HTTPS host (for example, a GitHub Pages site or Netlify).
2. Open the deployed HTTPS site in Safari on the iPhone.
3. Tap Share -> Add to Home Screen -> Add.
4. Launch FORGE from the new Home Screen icon.
5. Allow camera access when scanning a barcode.

The camera scanner and product lookup require internet access. The app shell can be cached for later visits after its first successful load.
