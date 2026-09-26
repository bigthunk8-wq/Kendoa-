# Kendoa — installable web app (PWA)

Free, works on Android and iPhone, installs to the home screen.

## Put it online (GitHub Pages, free, from your phone)

1. Go to github.com and create a free account, if you don't have one.
2. Tap **+** → **New repository**. Name it `kendoa`. Make it Public. Create it.
3. Tap **Add file → Upload files**. Upload every file in this folder
   (`index.html`, `manifest.json`, `sw.js`, and the `icons` and `images` folders,
   keeping the same folder names). Commit the changes.
4. Go to the repository's **Settings → Pages**. Under "Branch", choose `main`
   and folder `/ (root)`, then Save.
5. Wait a minute, then your app is live at:
   `https://YOUR-USERNAME.github.io/kendoa/`

## Install it like an app

1. Open that link in Chrome (Android) or Safari (iPhone).
2. Android: tap the **⋮ menu → Install app** (or "Add to Home screen").
   iPhone: tap **Share → Add to Home Screen**.
3. The Kendoa icon appears on your home screen and opens full-screen, no
   browser bar — it behaves like an installed app.

## What's inside

- Home, Categories, Product, Cart, Orders, Profile — matching your design
- Sell on Kendoa: My Shop + Add product, with real photo uploads from the
  phone's camera or gallery
- Works offline after the first visit (service worker)
- Everything (products, cart, orders) is saved on the phone using the
  browser's storage, so it's still there after closing the app

## Limits of this version

- Each phone has its own separate storage — a product someone else adds on
  their phone won't show up on yours yet.
- No sign-in yet.

The next step is connecting a shared database (Supabase, free) so every
seller's products show up for every buyer, and people can create real
accounts.
