# RepCity — website

Landing page, privacy policy and terms of use for RepCity (iOS). Static HTML and CSS, no build step, no
dependencies. Fonts on the home page come from Google Fonts; everything else is in `assets/`.

- `index.html` the home page
- `privacy.html` the privacy policy — the URL App Store Connect and the app point at
- `terms.html` the terms of use — the subscription's Terms of Use link
- `home.css` the home page's styles; `styles.css` the policy pages' styles
- `assets/`
  - `app-icon.png` the app icon, 256px; `favicon.png` 64px
  - `city-screen.jpg` an in-game render of a grown city (the phone in the hero)
  - `city-day1.jpg`, `city-day30.jpg` the onboarding's day 1 / day 30 pair (the slider)
  - `goal-hundred.jpg` the 100 a Day art

Contact: contacttouchstonetech@gmail.com

## Publishing

Served by GitHub Pages from `main` at the repository root: Settings → Pages → Source: Deploy from a branch → main /
(root). `.nojekyll` is present so Pages serves the files as they are.

## Before launch

The status pill in the hero reads *For iPhone · iOS 18+*. Add an App Store badge linking to the app once it's
approved.

Keep the privacy policy and the App Store privacy labels in line with the services the released app uses (Apple
iCloud and Game Center, Google Firebase Analytics and Crashlytics).

## Source

The site's source also lives in the app's private repository, in `Website/`.
