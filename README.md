# Tip Book

A simple app for restaurant servers to track hours, cash tips and paychecks.

- Pick start and finish times; hours are worked out for you
- Each day is split into a first half and a second half
- Checks each paycheck against the hours you logged
- Shows what you're on track to earn this year and your real hourly rate
- Downloads everything as an Excel file
- Voice input in Mandarin (简体 or 繁體) or English: tap the microphone and say your times and tips

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

## Voice input 语音输入

Tap **用普通话语音填写** on either half of the day and talk, for example:
“上午十点到下午三点半，休息半小时，现金小费八十五块”.

- Your words appear in a text box as you speak. Tap the box to fix any word; the times and tips below update as you type.
- Tap **确认填入** to fill in the day.
- If the microphone does not work, Tip Book switches by itself to keyboard voice typing: tap the text box, then the 🎤 on the iPhone keyboard.
- **Settings → Voice input → 检查语音功能** checks the phone and explains how to fix any problem.

If voice does not work on iPhone:
1. Settings → General → Keyboard → turn on **Enable Dictation**.
2. Settings → General → Keyboard → Keyboards → add **Chinese, Simplified (Pinyin)**.
3. In Safari, tap **aA** → Website Settings → Microphone → **Allow**.
4. Some iOS versions block speech recognition in Home Screen apps. Open the link in Safari, or use the keyboard 🎤.
