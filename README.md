 💰 My Finance Tracker
### A personal finance app built by Rain

A beautiful, private, mobile-first finance tracker that works on iPhone, Android, and desktop browsers — no app store needed.

---

## ✨ What this app does

| Section | What you can track |
|---|---|
| 🛍 **Wishlist** | Items you want to buy, with EMI calculator if buying on credit card |
| 🧾 **Expenses** | Daily spending with categories, search, and filter |
| 💰 **Income** | Salary, freelance, and other income sources |
| ↔️ **Money Owed** | Debts you owe and money others owe you, with partial payment tracking |
| 🏦 **Savings** | FD, mutual funds, SIP, gold, stocks, PPF — all in one place |
| 🔁 **Recurring** | Auto-tracked monthly expenses like rent, subscriptions |
| 📊 **Insights** | Charts — spending by category, monthly trend, savings vs wishlist, debt map |
| 📅 **Summary** | Monthly report cards for every month |
| ⚙️ **Settings** | PIN lock, Face ID, GIF celebrations, custom categories, budget, light/dark mode |

---

## 🎬 GIF Celebrations

The app plays a full-screen GIF popup when you:
- Log income
- Add a wishlist item or mark one as bought
- Log an expense milestone
- Add a saving or hit a savings milestone
- Log a debt payment or fully clear a debt

Go to **Settings → GIF Celebrations** to upload up to **3 GIFs per trigger**. It picks one randomly each time.

---

## 🔒 Security

- **PIN lock** — 4-digit PIN set on first launch
- **Face ID** — on iPhone (Safari) using Web Authentication API
- **Auto-lock** — locks after inactivity (configurable in Settings)
- **Lock button** — manually lock anytime from the header
- All data is stored **only on your device** — nothing is sent anywhere

---

## 📱 How to install on iPhone

1. Open your app link in **Safari** (e.g. `my-finance-tracker.vercel.app`)
2. Tap the **Share** button (box with arrow at bottom)
3. Tap **"Add to Home Screen"**
4. Tap **Add**

The app will appear on your home screen and open full-screen like a native app.

---

## 🤖 How to install on Android

1. Open your app link in **Chrome**
2. Tap the **three dots menu** (top right)
3. Tap **"Add to Home screen"**
4. Tap **Add**

Works on Samsung Internet browser too.

---

## 🔗 How to share with others

Each person who opens the link gets their **own private data** stored on their own device. Your data and their data are completely separate — sharing the link does not share your data.

**To share:**
- Just send them your Vercel link: `https://your-app-name.vercel.app`
- They open it in Chrome (Android) or Safari (iPhone)
- They add it to their home screen
- They set their own PIN
- Done — they have their own copy with their own data

---

## 🛠 How to update the app

1. Go to [github.com](https://github.com) → your `my-finance-tracker` repository
2. Click on `index.html`
3. Click the **pencil icon** (Edit)
4. Make your changes or paste a new version
5. Click **"Commit changes"**
6. Vercel automatically updates the live app within **~60 seconds**

---

## 📁 Files in this project

```
my-finance-tracker/
├── index.html        ← The entire app (one file)
├── manifest.json     ← Makes it installable as an app on phones
└── icon.jpeg         ← App icon shown on home screen
```

---

## 🧰 Tech used

- Plain **HTML, CSS, JavaScript** — no frameworks, no build tools
- **localStorage** — saves your data on your device
- **Chart.js** — for the graphs and charts
- **Web Authentication API** — for Face ID on iPhone
- **PWA (Progressive Web App)** — makes it installable on any phone
- **Vercel** — free hosting

---

## 💡 Features at a glance

- ✅ PIN + Face ID lock
- ✅ Auto-lock after inactivity
- ✅ Light mode / Dark mode
- ✅ EMI calculator for credit card purchases
- ✅ Debt payment tracker with progress bar
- ✅ Custom expense categories
- ✅ Search and filter expenses
- ✅ Monthly budget meter with warnings
- ✅ "Can I afford this?" calculator
- ✅ Recurring expenses (auto-logged monthly)
- ✅ Monthly summary report cards
- ✅ GIF celebration popups (up to 3 per trigger, random pick)
- ✅ Export data as JSON backup
- ✅ Works offline
- ✅ Installable on iPhone and Android

---

*Built with Claude — Anthropic AI*
