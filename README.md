# Ghana Mega Shop — Android, iPhone and Website Starter

A mobile-first, single-owner ecommerce storefront for Ghana. This is a static Progressive Web App (PWA) starter that can be published on HTTPS hosting and added to supported phone home screens.

## Store settings
- Store name: Ghana Mega Shop
- Currency: Ghana cedis (GH₵)
- WhatsApp ordering number: 0533006099 (international format: 233533006099)
- Seller model: own products only
- Categories: home appliances, electrical products, phones/electronics, clothes, shoes, bags, general merchandise

## Included
- Responsive storefront for phone, tablet and desktop
- Product categories, search and sorting
- Sample product cards and prices (replace these before selling)
- Cart saved only in the current browser/device
- Checkout form that opens WhatsApp with a prepared order message
- PWA manifest, service worker, SVG and PNG icons including an iPhone home-screen icon

## Publish free using only your phone (GitHub Pages)
1. Open https://github.com in Chrome and sign in or create an account.
2. Create a **public** repository named `ghana-mega-shop`.
3. Open the repository and choose **Add file → Upload files**.
4. Upload the files in this folder directly (not a folder containing them): `index.html`, `manifest.webmanifest`, `service-worker.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, and `README.md`.
5. Commit the files to the `main` branch.
6. Open **Settings → Pages**. Under Build and deployment, choose deploy from a branch, select `main` and `/(root)`, then Save.
7. Wait for GitHub Pages to show the published HTTPS URL. Open it and test the cart and WhatsApp checkout.

## Add to phone home screen
- Android: open the HTTPS website in Chrome, open the menu, and choose **Install app** or **Add to Home screen** if offered.
- iPhone: open the HTTPS website in Safari, tap **Share**, then **Add to Home Screen**.
- Computer: customers can visit the website link directly.

These create an app-like web experience. They do **not** publish a native app in Google Play or Apple's App Store. Native store releases require separate build, testing, developer accounts and store review; Apple distribution can require a paid developer membership.

## Before launch
1. Replace the sample products and prices with real products you actually have.
2. Test WhatsApp ordering and confirm that the number is correct.
3. Set your delivery fees, delivery areas, returns policy and payment instructions.
4. Test on Android and, if possible, an iPhone.

## Important limitations
This is a prototype storefront, not a complete production ecommerce backend. It has no secure admin login, shared online product database, central order storage, stock synchronisation, integrated Mobile Money/card payments, delivery tracking, or customer accounts. Cart data is local to each browser/device. WhatsApp receives a prepared message; the customer must send it and you must confirm the order. Do not request customer PINs or OTPs. Never claim a payment is received until you verify it through your provider.
