# 💳 Walletix — Premium Expense Tracker

<div align="center">

![Walletix](icon-192.png)

**A beautifully designed, privacy-first expense tracker — built as a Progressive Web App.**

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://walletix.netlify.app/)
[![PWA](https://img.shields.io/badge/PWA-Ready-5A0FC8?style=for-the-badge&logo=pwa)](https://walletix.netlify.app/)
[![License](https://img.shields.io/badge/License-Personal%20Use-blue?style=for-the-badge)](LICENSE)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 💰 **Transaction Tracking** | Add income & expense with categories, description & date |
| 📊 **Monthly Analytics** | Bar charts + category-wise spending breakdown |
| 🎯 **Budget Tracker** | Set monthly or custom date range budgets per category |
| 🗑️ **Clear Records** | Delete transactions by month, range, or all at once |
| ❤️ **Liked / Favorites** | Save frequently used transaction patterns |
| 🌙 **Dark / Light Mode** | Smooth theme toggle — preference saved automatically |
| 📱 **Fully Responsive** | Optimized for both mobile and desktop |
| 📲 **PWA Installable** | Install as a native app on Android & iOS |
| 🔒 **100% Private** | All data stored locally — no server, no account needed |
| ⚡ **Offline Support** | Works without internet after first load |

---

## 📸 Screenshots

> <img width="340" height="228" alt="Screenshot 2026-03-23 023301" src="https://github.com/user-attachments/assets/ec4fad42-a9a8-4b20-a147-8a651c02f168" />
<img width="301" height="447" alt="Screenshot 2026-03-23 023213" src="https://github.com/user-attachments/assets/379f4866-c91d-4467-b577-dda104079592" />
<img width="288" height="451" alt="Screenshot 2026-03-23 023154" src="https://github.com/user-attachments/assets/c47ff2c5-8196-49da-8e30-28c8996810c8" />
<img width="317" height="448" alt="Screenshot 2026-03-23 023024" src="https://github.com/user-attachments/assets/81ef2f8e-77c6-46e2-92dc-600dbb3f8d2d" />
<img width="321" height="44" alt="Screenshot 2026-03-23 023013" src="https://github.com/user-attachments/assets/c4e774c8-a9e4-4430-90c6-6a70f006b34e" />

---

## 🛠️ Tech Stack

- **HTML5** — Semantic structure
- **Vanilla CSS3** — CSS variables, grid, animations, responsive design
- **Vanilla JavaScript** — No frameworks, pure JS logic
- **Lucide Icons** — Beautiful open-source icon library
- **localStorage** — Client-side data persistence
- **Service Worker** — Offline caching & PWA support

---

## 🚀 Getting Started

### Option 1 — Open directly
```bash
# Just open in browser
open index.html
```

### Option 2 — Local server (for PWA features)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using VS Code
# Install "Live Server" extension → Right click index.html → Open with Live Server
```
Then open: `http://localhost:8000`

---

## 📂 File Structure

```
walletix/
├── index.html       # Complete app — UI, styles & logic
├── manifest.json    # PWA manifest — icons, theme, display mode
├── sw.js            # Service Worker — offline caching
├── icon-192.png     # App icon (192×192)
├── icon-512.png     # App icon (512×512)
└── README.md        # This file
```

---

## 📲 Install as App (PWA)

### Android (Chrome)
1. Open the live link in **Chrome**
2. Tap **⋮ Menu** → **"Add to Home Screen"**
3. Tap **"Install"** → App installed! ✅

### iPhone / iPad (Safari)
1. Open the live link in **Safari**
2. Tap **Share ⬆** button
3. Tap **"Add to Home Screen"**
4. Tap **"Add"** → App installed! ✅

---

## 💡 Usage Guide

### Adding a Transaction
1. Select **Expense** or **Income** tab
2. Enter **Amount** (required)
3. Enter **Description** *(optional — auto-fills from category)*
4. Choose **Category**
5. Select **Date**
6. If category is "Other" → enter custom name
7. Tap **"Add Transaction"**

### Setting a Budget
1. Tap **"+ Budget"** in header
2. Select **Category**
3. Choose **Period**:
   - 📅 **Monthly** — tracks current month spending
   - 📆 **Custom** — set your own start & end date
4. Enter **Budget Limit**
5. Tap **Save** — budget tracker shows real-time progress

### Clearing Records
1. Tap 🗑️ **trash icon** in header
2. Choose what to clear:
   - This Month
   - Last 3 / 6 Months
   - This Year
   - Custom Date Range
   - ALL Records
3. Preview shows how many transactions will be deleted
4. Confirm → Done ✅

### Analytics
- Go to **Analytics** tab
- Tap any **month pill** to see that month's details
- Tap **bar in chart** to drill down
- See spending breakdown by category

---

## 🔒 Data & Privacy

```
Your Data Flow:
Phone/PC Browser → localStorage → Stays on YOUR device

❌ No server
❌ No database  
❌ No account required
❌ No data sent anywhere
✅ 100% private
✅ Works offline
```

> ⚠️ **Note:** Clearing browser cache or site data will erase your transactions.
> Export feature coming soon!

---

## 🔄 Deployment (Netlify)

### One-time GitHub Setup
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/yourusername/walletix.git
git push -u origin main
```

### Connect to Netlify
1. Go to [app.netlify.com](https://app.netlify.com)
2. **"Add new site"** → **"Import from GitHub"**
3. Select **walletix** repo
4. Deploy! ✅

### Auto-Deploy
Every `git push` → Netlify automatically deploys! 🚀

```bash
# Update workflow
git add .
git commit -m "v1.2 - Added export feature"
git push
# → Live in ~30 seconds!
```

---

## 🗺️ Roadmap

- [ ] Export data as CSV / JSON
- [ ] Import data (backup restore)
- [ ] Recurring transactions
- [ ] Multiple currencies
- [ ] Custom categories
- [ ] Widgets / home screen summary

---

## 👨‍💻 Developer

**Built by** — *speedy*

[![GitHub](https://img.shields.io/badge/GitHub-vkukadiya22-181717?style=flat&logo=github)](vkukadiya22)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-vedk-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/ved-k-552337388?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

## 📄 License

This project is for **personal use and portfolio** purposes.
Feel free to fork and modify for your own use.

---

<div align="center">
Made with ❤️ | No subscriptions. No ads. Just your money.
</div>
