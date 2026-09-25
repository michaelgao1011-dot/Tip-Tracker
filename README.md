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

Tip Book opens in **Safari** from your Home Screen. This lets iPhone remember "Allow" for the microphone, so it asks only once.

1. Open your link in **Safari**.
2. Tap **aA** (left of the address) → **Website Settings** → **Microphone** → **Allow**.
   Or for all websites: Settings → Apps → Safari → Microphone → **Allow**.
3. Tap **Share** → **Add to Home Screen** → **Add**.

### Moving from the old Home Screen app
The old icon keeps its data separately. Before deleting it:
1. Open the old icon → Settings → **Save a backup** → save to Files.
2. Delete the old icon.
3. Open the link in Safari → Settings → **Restore from a backup** → pick the file.
4. Add to Home Screen again (step 3 above).

## One-tap voice with Siri (no permission pop-ups)

Build a Shortcut once (Settings → "Siri 一键说话" in the app shows the same steps and a Copy button for your address):
1. Shortcuts app → **+**
2. **Dictate Text** (听写文本): Language Chinese (China mainland), Stop Listening: After Pause
3. **URL Encode** the Dictated Text
4. **URL**: `https://YOUR-USERNAME.github.io/tipbook/?say=` then insert **URL Encoded Text** at the end
5. **Open URLs**
6. Name it **记小费**, then **Add to Home Screen**

Tap 记小费 or say "嘿Siri，记小费", then talk, for example “晚班五点到十点半，小费一百二十块”. Tip Book opens with the text filled in; fix any word and tap **确认填入**. Saying 午班/晚班 (or 上半天/下半天) picks the half; 昨天 logs yesterday.

## Your data

Everything is saved on your phone only. Nothing is sent anywhere.
Safari may clear website data if you don't open Tip Book for 7 days, so the app reminds you to save a backup each week.
Use **Settings → Save a backup** now and then and keep the file in Files or email it to yourself.
If you get a new phone, open the app and use **Restore from a backup**.

## Updating the app

Upload the new `index.html` to the same repository, and change `VERSION` at the top of `sw.js` (for example `tipbook-v2`) so phones pick up the change.

## Voice input 语音输入

On iPhone, Tip Book uses the **iPhone keyboard's dictation** by default. iPhone asks for permission only once, and it uses Apple's full Mandarin recognition.

1. Tap **用普通话语音填写** on either half of the day. A text box opens with the keyboard.
2. If the keyboard isn't Chinese, tap 🌐 and choose **简体拼音**. iPhone remembers this next time.
3. Tap the 🎤 below the keyboard and say, for example: “上午十点到下午三点半，休息半小时，现金小费八十五块”.
4. Your words appear in the box. Fix anything by typing; the times and tips update as you type.
5. Tap **确认填入**.

One-time iPhone setup: Settings → General → Keyboard → turn on **Enable Dictation**, and add **Chinese, Simplified (Pinyin)** under Keyboards.

To use the web microphone instead, change **Settings → Voice input → Voice method**. **检查语音功能** tests it and explains any problem.
