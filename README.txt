ONYII DIGITAL — installable web-app prototype

CONTENTS
- index.html: responsive storefront with product filters, cart, and checkout preview
- manifest.webmanifest: web-app installation metadata
- icon.svg: black-and-silver app icon
- sw.js: basic offline caching for the front-end

PREVIEW
Open index.html locally to preview the storefront. Installability and service-worker/offline features require the site to be hosted over HTTPS (or localhost).

IMPORTANT: NOT YET A LIVE STORE
This package does not process real payments, create secure customer accounts, store orders, or automatically deliver paid files. Those features require a secure backend and a payment provider that supports the business's location and account type. Never put private API keys in front-end files. Before publishing, verify platform eligibility, age requirements, privacy terms, and payment/payout support. An adult may need to manage hosting/payment accounts if the provider requires it.

DEPLOY
Upload the contents of this folder (not the ZIP itself) to a static HTTPS host. After the site is live over HTTPS, test it on Android Chrome and use the browser's install/add-to-home-screen option where available.
