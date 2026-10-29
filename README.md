# أفق – Arabic Finance PWA Demo

A mobile-first RTL interface inspired by modern financial apps, without using any real bank logo or credentials. Data, account numbers, payments and transfers are **simulated** and stored locally; this is not a banking service.

## Run and deploy

Static files, no build tools needed. The entry is index.html. For a public URL use GitHub Pages: in repository **Settings → Pages → Build and deployment**, select **Deploy from a branch**, **main**, **/(root)**, then Save.

Site after GitHub Pages activation: https://ibr7h.github.io/afaq-finance-pwa/

For iOS, open the website in Safari and choose **Share → Add to Home Screen**. The app shell is cached by a service worker after the first successful online visit.

## Features

- Home, accounts, payment cards, account details, sample transfers and bill payments
- Arabic right-to-left typography, accessible mobile controls, iPhone safe areas
- A visible non-JavaScript homepage fallback (no blank page)
- Demo PIN: 12345 (not a genuine authentication mechanism)
- Manifest, app icons and offline app-shell cache

**Security:** Do not enter real PINs, financial data or personal banking details. This version does not perform real authentication, financial operations or Face ID verification. Do not connect it to production financial services without appropriate server-side security and regulatory review.
