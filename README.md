# sentry-test

This repo is intended to reproduce the following bug:
https://github.com/getsentry/sentry-capacitor/issues/217

To show the error:
- Pull the repo local
- `npm ci`
- `npm run build`
- `npx cap sync`

## How this project was created
- Used the Ionic CLI to create a blank Ionic starter for latest Ionic Angular with Capacitor
- Added the iOS platform
  - `npm i @capacitor/ios`
  - `npx cap add ios`
- Verified it all built and did a `cap sync` properly
  - `npm ci`
  - `npm run build`
  - `npx cap sync`
- Then, added `@sentry/capacitor`
  - `npm i @sentry/capacitor`
