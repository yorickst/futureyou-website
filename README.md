# FutureYou Website

Static App Store support website for FutureYou.

## Pages

- `index.html` - landing page
- `privacy.html` - App Store privacy policy URL
- `terms.html` - optional terms page
- `support.html` - App Store support URL

## Before Publishing

Support email used by the site: `futureyou.support@gmail.com`.

## Hosting

Simple options:

- GitHub Pages: publish the `website` folder.
- Firebase Hosting: set `website` as the public directory.

Recommended App Store URLs after publishing:

- Marketing URL: homepage
- Privacy Policy URL: `/privacy.html`
- Support URL: `/support.html`

The terms page is not usually required for a simple iOS app using Apple's standard App Store terms, but keeping `/terms.html` available is useful when the app has subscriptions, accounts, user content, or extra usage rules.
