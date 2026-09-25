# Tip Book

A simple app for restaurant servers to track hours, cash tips and paychecks.

- Pick start and finish times; hours are worked out for you
- Each day is split into a first half and a second half
- Checks each paycheck against the hours you logged
- Shows what you're on track to earn this year and your real hourly rate
- Downloads everything as an Excel file

## Put it online with GitHub Pages (free)

1. Sign in to github.com and click **New repository**. Name it `tipbook`, set it to **Public**, and click **Create repository**.
2. Click **uploading an existing file**. Unzip this folder on your computer and drag in **everything inside it**: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. Click **Commit changes**.
3. Go to **Settings → Pages**. Under **Branch**, choose `main` and `/ (root)`, then click **Save**.
4. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/tipbook/`

## Add it to your iPhone

1. Open the link above in **Safari** (it must be Safari).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open Tip Book from your home screen. It runs full screen like a regular app and works without internet after the first open.

## Your data

Everything is saved on your phone only. Nothing is sent anywhere.
Use **Settings → Save a backup** now and then and keep the file in Files or email it to yourself.
If you get a new phone, open the app and use **Restore from a backup**.

## Updating the app

Upload the new `index.html` to the same repository, and change `VERSION` at the top of `sw.js` (for example `tipbook-v2`) so phones pick up the change.
