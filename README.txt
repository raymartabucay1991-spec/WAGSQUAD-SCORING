# WAGSQUAD-SCORING PWA

This package contains the WAGSQUAD-SCORING web app converted into a Progressive Web App.

## Files
- index.html — original app with PWA metadata and service-worker registration
- manifest.json — Home Screen/app configuration
- service-worker.js — offline caching
- icons/ — app icons

## Deploy
Upload the contents of this folder to an HTTPS static host such as GitHub Pages, Netlify, or another static web host.

Then on iPhone:
1. Open the HTTPS website in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Open WAGSQUAD-SCORING from the Home Screen.

## Important
The existing score/trend/GAP/BIAS/filter logic and localStorage keys are preserved.
