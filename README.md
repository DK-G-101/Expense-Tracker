# 💰 Expense Tracker — Auto Sync to Google Sheets

Every expense you add is **automatically saved to your Google Sheet** in real time.

## How it works
1. You add an expense in the app
2. It saves instantly to your phone (local storage)
3. It syncs immediately to your Google Sheet via API
4. If offline, it queues and syncs automatically when you're back online

## Your Google Sheet
https://docs.google.com/spreadsheets/d/1vnt4PV8DzEFqIHvMePrgQ8S9YBUzSlD2wnu94XyLf64/edit

---

## Deploy to Vercel — Step by Step

### Step 1: Upload to GitHub
1. Go to github.com → sign in → click **New repository**
2. Name it `expense-tracker` → click **Create repository**
3. Upload ALL these files:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `vercel.json`
   - `icon-192.png`
   - `icon-512.png`

### Step 2: Deploy on Vercel
1. Go to vercel.com → sign in with GitHub
2. Click **Add New Project** → select your `expense-tracker` repo
3. Click **Deploy**
4. You get a free URL like `expense-tracker-xyz.vercel.app`

### Step 3: Install on your Android phone
1. Open your Vercel URL in **Chrome** on your phone
2. Tap the **⋮ menu** (top right) → tap **"Add to Home screen"**
3. Tap **Add**
4. The app icon appears on your home screen!

---

## Files
```
expense-tracker/
├── index.html      ← full app with Google Sheets sync
├── manifest.json   ← PWA config
├── sw.js           ← offline support
├── vercel.json     ← Vercel config
├── icon-192.png    ← app icon
└── icon-512.png    ← app icon (large)
```
