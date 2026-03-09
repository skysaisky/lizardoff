# 🦎 LizardOFF — Play Store Publishing Guide
## Step-by-Step for Beginners

---

## ✅ WHAT YOU HAVE
Your app is a **PWA (Progressive Web App)** — it works on any browser AND can be converted
into a real Android APK to upload on Google Play Store.

---

## 📦 STEP 1 — Host Your App Online (FREE)

You need your app to be live on a website URL first.

### Option A: Netlify (Easiest — Recommended)
1. Go to **https://netlify.com** → Sign up free
2. Drag your entire `lizardoff` folder onto the Netlify dashboard
3. You'll get a free URL like: `https://lizardoff.netlify.app`
4. ✅ Done! Your app is live.

### Option B: GitHub Pages (Also Free)
1. Create a free account at **https://github.com**
2. Create a new repository called `lizardoff`
3. Upload all your files there
4. Go to Settings → Pages → Enable GitHub Pages
5. You'll get: `https://yourusername.github.io/lizardoff`

---

## 📱 STEP 2 — Convert to Android APK (FREE)

1. Go to **https://www.pwabuilder.com**
2. Paste your website URL (from Step 1)
3. Click **Start** → wait for it to analyze your app
4. Click **Package for Stores**
5. Choose **Google Play** → Click **Generate Package**
6. Download the `.aab` file (Android App Bundle)
7. Also download the **signing key** — save it safely! You'll need it forever.

---

## 🏪 STEP 3 — Create Google Play Developer Account

1. Go to **https://play.google.com/console**
2. Sign in with your Google account
3. Pay the **one-time $25 registration fee**
4. Fill in your developer profile details
5. Accept the agreements

---

## 🚀 STEP 4 — Upload Your App

1. In Google Play Console → Click **Create App**
2. App name: `LizardOFF`
3. Default language: English
4. App or Game: **App**
5. Free or Paid: **Free**
6. Click **Create**

### Fill in App Details:
- **Short description**: "Ultrasonic sound to repel lizards from your home"
- **Full description**: "LizardOFF uses ultrasonic high-frequency sound waves to keep lizards away from your home. Features adjustable frequency (15–25 kHz), multiple waveform types, and auto-off timer. Works best when phone volume is at maximum."
- **Category**: Tools
- **App icon**: Use the `icon-512.png` from the icons folder
- **Screenshots**: Take screenshots of your app on a phone

### Upload the APK:
1. Go to **Production** → **Create new release**
2. Upload the `.aab` file you downloaded from PWABuilder
3. Click **Save** → **Review release** → **Start rollout**

---

## ⏳ STEP 5 — Wait for Review

- Google reviews usually take **1–3 days**
- You'll get an email when your app is approved
- Once approved, your app is LIVE on the Play Store! 🎉

---

## 💡 TIPS FOR GETTING APPROVED

✅ Make sure your app description is clear and honest
✅ Add at least 2 screenshots showing the app
✅ Your app icon must be 512×512 PNG
✅ Don't use the word "free" in your app name
✅ Set content rating to "Everyone"

---

## 📞 NEED HELP?

- PWABuilder Docs: https://docs.pwabuilder.com
- Play Console Help: https://support.google.com/googleplay/android-developer
- Netlify Docs: https://docs.netlify.com

---

*LizardOFF v2.0 — Good luck with your app! 🦎⚡*
