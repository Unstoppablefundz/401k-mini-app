# Vault401k – 401(k) Tracker Mini App

**Track your 401(k) balance & growth — right inside Telegram!**

---

## Live Bot
[@Vault401k_bot](https://t.me/Vault401k_bot)  
**Tap "Open 401k" to start!**

---

## Features
- Real-time 401(k) balance
- Add contributions instantly
- 10-year growth projection (7% avg)
- **Saves per user** (via Telegram ID)
- **No backend, no cost, no login**
- Beautiful glass-style UI

---

## How to Use
1. Open: [@Vault401k_bot](https://t.me/Vault401k_bot)
2. Tap **"Open 401k"**
3. Start tracking!

---

## Setup (For Developers)

### 1. Deploy (Free)
- Go to [Vercel](https://vercel.com)
- Import this repo
- Deploy → Get URL

### 2. Link to Bot
1. Talk to **@BotFather**
2. Send: `/setmenubutton`
3. Select: **@Vault401k_bot**
4. Button Text: `Open 401k`
5. URL: `https://your-app.vercel.app`

---

## Tech
- **Telegram Web Apps**
- **Vercel** (free hosting)
- **localStorage** (per user)
- Pure HTML/CSS/JS

---

## Customize
Edit `index.html`:
```js
let balance = 45230;     // ← Your starting balance
let yearlyContrib = 8500; // ← Annual contribution
