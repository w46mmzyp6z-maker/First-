# ReelScore — iOS-compatible PWA

This version is designed for iPhone Safari and can be installed to the Home Screen.

## Install on iPhone
1. Put these files on a web host using HTTPS.
2. Open the site in Safari on iPhone.
3. Tap Share.
4. Choose **Add to Home Screen**.
5. Open ReelScore from the new Home Screen icon.

## Local testing
A PWA/service worker normally needs HTTPS or localhost. Opening the HTML file directly will still run the analyzer, but offline/install features require hosting.

## Current features
- iPhone-responsive UI
- Home Screen / standalone mode
- Safe-area support for modern iPhones
- Offline caching after first load
- Reel upload and preview
- Instagram Insights entry
- 0–100 optimization score
- Category diagnostics and prioritized recommendations

## Next step for a true App Store app
Wrap the same product in a native iOS shell (SwiftUI/WebKit) or rebuild the interface in SwiftUI, then add secure Meta/Instagram OAuth and the Instagram Graph API for eligible professional accounts.
