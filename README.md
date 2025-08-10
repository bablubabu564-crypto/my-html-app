
# Neon Cyberpunk Racer - PWA (Bablu)

This folder contains a ready-to-publish Progressive Web App (PWA) version of the Neon Cyberpunk Racer game.
Files included:
- index.html  -> main game
- manifest.json -> PWA manifest
- sw.js -> simple service worker for offline caching
- icons/ -> PWA icons (192x192, 512x512)

## How to publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload all files and folders from this package to the repo root.
3. In repo Settings -> Pages, set the branch to `main` (or `master`) and the folder to `/ (root)` and save.
4. After a minute, your site will be available at `https://<your-username>.github.io/<repo-name>/`
5. Open that URL on a phone, tap menu -> Add to Home screen to install as PWA.

## How to build an Android APK from this PWA
- Use PWABuilder (https://www.pwabuilder.com) to generate Android package
  - Enter your GitHub Pages URL and follow the steps to produce an Android app or a Trusted Web Activity (TWA).
- Alternatively use tools like `bubblewrap` or `PWABuilder`'s downloadable project and build with Android Studio.

## Notes
- For testing locally on your phone, you can host this repo on GitHub Pages or any static host (Netlify, Vercel).
- If you want a signed APK for Play Store, you'll need to build in Android Studio and sign the app with your keystore.
