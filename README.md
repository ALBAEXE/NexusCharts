<div align="center">

<img src="logo-icon.png" alt="NexusCharts" width="120">

# NexusCharts

**Real-time charts, indicators, scripts and alerts — right in your pocket.**
A fast, beautiful charting app for iPhone, Android and desktop, with a pure-black, orbit-inspired design.

**English** · [Italiano](README.it.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md)

[![Version](https://img.shields.io/badge/version-v1.0.1-d9a441?style=for-the-badge)](../../releases)
![Platform](https://img.shields.io/badge/iPhone%20%7C%20Android%20%7C%20Desktop-web%20app-2962ff?style=for-the-badge)
![Languages](https://img.shields.io/badge/languages-IT%20%7C%20EN%20%7C%20ES%20%7C%20FR%20%7C%20DE-22ab94?style=for-the-badge)
![Price](https://img.shields.io/badge/install-free-111111?style=for-the-badge)

</div>

<div align="center">
<table>
  <tr>
    <td align="center" width="25%"><img src="screenshots/en/01-welcome.png" width="190" alt="Welcome"><br><sub>1. Welcome</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/02-sign-in.png" width="190" alt="Sign-in"><br><sub>2. Sign-in</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/03-watchlist.png" width="190" alt="Watchlist"><br><sub>3. Watchlist</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/04-signals.png" width="190" alt="Signals"><br><sub>4. Signals</sub></td>
  </tr>
  <tr>
    <td align="center" width="25%"><img src="screenshots/en/05-chart-drawings.png" width="190" alt="Chart & drawings"><br><sub>5. Chart & drawings</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/06-indicators.png" width="190" alt="Indicators"><br><sub>6. Indicators</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/07-script-editor.png" width="190" alt="Script editor"><br><sub>7. Script editor</sub></td>
    <td align="center" width="25%"><img src="screenshots/en/08-bar-replay.png" width="190" alt="Bar Replay"><br><sub>8. Bar Replay</sub></td>
  </tr>
</table>
</div>

---

## 📖 Contents

- [What is NexusCharts](#-what-is-nexuscharts)
- [Features](#-features)
- [Installation](#-installation)
- [How to get access](#-how-to-get-access)
- [Compatibility](#-compatibility)
- [Privacy & security](#-privacy--security)
- [How it's built](#%EF%B8%8F-how-its-built)
- [Versioning](#-versioning)
- [FAQ](#-faq)
- [Roadmap](#-roadmap)
- [Credits](#-credits)

---

## ✨ What is NexusCharts

NexusCharts is a **web app** that installs on your Home Screen and works like a real app: full screen, with its own icon, no App Store needed.
It's built for traders who want **clean charts, live prices, indicators and drawing tools** on their phone, without limits, ads or subscriptions.

| | |
|---|---|
| ⚡ **Live prices** | Prices stream live from our own data server, often several times per second |
| 📈 **42 indicators + your scripts** | Built-in library and a Pine Script™-compatible engine |
| 🔔 **Real alerts** | Push notifications even when the app is closed |
| 📱 **Native feel** | Full screen, haptic feedback, smooth animations, no browser bars |
| 🔄 **Always updated** | Every time you open it you get the latest version automatically |
| 🌍 **5 languages · 2 themes** | Italian, English, Spanish, French, German · Dark and light |

> 📝 What's new in each version: see the [Releases](../../releases) page.

### 🆕 New in 1.0.1 — Updated welcome screen

- 👤 The last welcome screen now presents **NexusCharts accounts**: two fields (username and password), with a new text in all 5 languages.

### Previously in 1.0.0 — NexusCharts accounts, a new address, only our own data

- 🌐 **New address**: NexusCharts now lives at **[nexuscharts.app](https://nexuscharts.app)**. The old address takes you there automatically.
- 👤 **NexusCharts accounts**: sign-up open to everyone with a username, email and password. Unique usernames, strong passwords and a 6-digit email code to confirm the address.
- 🔐 **Easier sign-in**: sign in with username or email, **Forgot password** with an email code, **Face ID** through the iPhone keychain, and on iPhone the email code appears right above the keyboard.
- ⚙️ **Account section** in Profile: change email, change password, Privacy Policy, Sign out and **Delete account**.
- 📧 **Emails in 5 languages**: verification code, welcome, security notices (password or email changed) and account deletion confirmation.
- 📡 **Only our own data**: instrument list, candles and prices all come from the NexusCharts data server. Alerts with the app closed use the same prices as the chart.
- 📜 **[Privacy Policy](https://nexuscharts.app/privacy.html)** in 5 languages, also readable inside the app.
- ⚠️ With the new address the app is installed again on the Home Screen, and watchlists, drawings, scripts and alerts start from scratch.

### Previously in 0.46.0 — Our own data server and 72 instruments

- 📡 **Live streaming**: prices now come from the NexusCharts data server the moment they change (often several times per second), the same on every phone.
- 🌐 **72 instruments**: 43 Forex pairs, metals (gold in USD, EUR, GBP and AUD, silver, platinum, palladium, copper), WTI and Brent oil, natural gas, 10 indices (Dow Jones, S&P 500, Nasdaq 100, DAX, FTSE 100, Nikkei 225, ASX 200, CAC 40, Euro Stoxx 50, US Dollar Index) and 7 cryptocurrencies. Stocks are coming soon.
- ⏱️ **Seconds timeframes from live prices**: 1s, 5s, 10s and the others are now built from every live price.
- 🛟 **Automatic fallback**: if the data server does not answer, the chart switches back to the previous source by itself. Two sources are never mixed on the same chart.
- 🗂️ **Data sources** in Profile: where prices and candles come from, and what is coming next.
- 🏷️ **Instrument names in all five languages** (for example *Gold Spot / US Dollar*), **new icons** for copper, oil, natural gas and the dollar index, and the **original crypto icons**.

### Previously in 0.45.0 — Design 3.0 inside the app, multiple watchlists and Signals

- 🪐 **Design 3.0 inside the app**: Watchlist, Chart menus, Indicators, Script editor, Bar Replay and Profile now use the same orbit style as the sign-in screen, in dark and light theme. The candles on the chart stay clean.
- 📋 **Multiple watchlists**: create, rename and delete your own lists from *All watchlists*. Your usual list stays the main **Watchlist**, so nothing is lost when you update.
- 🛰️ **Signals**: long-press a pair and pick one of 7 colours. Each colour gets its own tab before *Watchlist* with the pairs of that colour from all your lists. Signals can be renamed or deleted.
- 🫙 **Empty states**: an empty list shows one clear empty box per category, and when no symbol is open the Chart shows *No symbol open* with a **Search a symbol** button (no data is loaded).
- ✏️ **Drawings**: crosshair placement that never hides the point under your finger, **line width** (1–4 px) and **style** (solid, dashed, dotted), and an **Undo** button (up to 30 steps per symbol).
- 📤 **Share**: a Design 3.0 preview of your chart first, then the system share sheet with the image only.
- 🧩 **Script editor minimap**: a coloured overview of your code on the right; tap or drag to jump.

<details>
<summary>Previously in 0.44.0 — German</summary>

- 🇩🇪 **German** is the fifth language of the app: sign-in, welcome screens, watchlist, chart, indicators, script editor, alerts, profile and install guide.
- 🔢 Numbers and dates in **German format** (for example 1.234,56).
- 🪐 The **orbit language menu** now has five round flags.
- 📲 The **Install** button on the sign-in screens now shows only its icon, on every device and in every language, the same size as the flag.

</details>

<details>
<summary>Previously in 0.43.0 — Design 3.0 sign-in</summary>

- 🔐 **New sign-in screen**, built exactly like the Design 3.0 prototype: orbit logo, Face ID scanner, console-style fields and gold and blue buttons with a rotating dashed ring.
- 🔢 **Access code in 8 boxes** (4 + 4): each character drops into its box and the eight segments around the logo light up one by one. A wrong code turns red and shakes.
- 💫 **Logo transition every time you open the app**, not only after the welcome screens.
- 🏳️ **Round language flags** everywhere in the app.
- 🧹 **Cleaner sign-in**: *Reset the app* is now only in Profile › Settings.
- 🖤 **0.43.1**: black launch screen and no more old glowing logo at startup, the new clean logo everywhere in the app, no yellow background when iPhone fills in your email and password, and an empty Server field shows only the green dot.
- 📲 **0.43.2**: the **Install** button is back on the sign-in screens (top right), in Design 3.0 style, with the step-by-step guide for iPhone and Android.

</details>

<details>
<summary>Previously in 0.42.0</summary>

- 🪐 **New welcome screens**: six short slides with the orbit logo, shown **once** on each device, then never again. You can skip them at any time.
- 💫 **Logo animation**: on every later launch the logo glides from the center to the top of the sign-in screen.
- 🌍 **Orbit language menu**: tap the flag to choose Italian, English, Spanish or French. Your choice is remembered.
- ⬛ **Pure-black sign-in screen** with bigger, modern buttons. Sign-in, codes and Face ID work exactly as before.

</details>

---

## 🚀 Features

### 📋 Watchlist
- 72 instruments: Forex, metals, energy, indices and crypto, grouped by category (stocks coming soon)
- Search any symbol and add it with one tap
- Live price, daily change in points and percent, flag/coin icons
- Mini player at the bottom with the selected symbol and its sparkline
- **Multiple watchlists** (*All watchlists*: create, rename, delete) and colour **Signals** with their own tabs
- Long-press a pair for Signal and Remove

### 📊 Chart
- Full-screen chart with **live updates** and a candle **countdown**
- **Timeframes:** seconds 1s · 5s · 10s · 15s · 30s · 45s — minutes 1m · 3m · 5m · 15m · 30m · 45m — hours 1H · 2H · 3H · 4H — days 1D · 1W · 1M · 3M · 6M · 12M
- **Chart types:** Candles · Bars · Line · Area · Heikin Ashi
- **Custom colors:** candle body, borders and wicks with opacity, plus canvas background and scales
- **Quick picker:** hold and swipe on the symbol or timeframe pill to change it instantly
- **Crosshair** with price and time labels and a **"+" button** for quick alerts
- **Compare** a second symbol in percentage mode
- Pinch to zoom, drag to scroll, share a snapshot of the chart

### 📈 Indicators
- **Indicators & metrics** screen with search, **Favorites** (tap the star) and **My scripts**
- **34 Technicals:** SMA, EMA, WMA, HMA, VWMA, ALMA, MA Ribbon, Bollinger Bands (+ %B and BandWidth), Keltner, Donchian, Envelopes, Supertrend, Ichimoku, VWAP, Linear Regression, RSI, Stoch RSI, Stochastic, MACD, CCI, ADX, ATR, MFI, Williams %R, Momentum, ROC, Awesome Oscillator, Aroon, OBV, Volume, Pivot Points, ZigZag
- **8 Fundamentals** (computed from prices): Previous Day High/Low, Previous Week High/Low, Daily Open, Average Daily Range, Daily Change %, Historical Volatility, 52-Week High/Low, Session High/Low
- **Compact legend:** tap an indicator to **show/hide** it, open its **settings** or **remove** it
- **Settings window** with **Inputs**, **Style** (visibility, color, width of each line) and **Visibility** (minutes / hours / days)
- **••• menu:** reset settings or **save as default** for the next time you add it

### 🧩 Script editor
- Write your own indicators in a **Pine Script™-compatible** language (v5/v6)
- Code editor with line numbers, error check and console
- Supports plots, shapes, boxes, lines, labels, tables, fills, inputs, alerts, higher timeframes and sessions
- Save your scripts and add them to the chart from **My scripts**
- **Minimap** of the code on the right: tap or drag to move through long scripts

### ✏️ Drawing tools
Saved automatically for each symbol.

| Group | Tools |
|---|---|
| Trend | Trend line · Horizontal line · Parallel channel |
| Forecasting & measurement | Long position · Short position (with target, stop and R:R) |
| Shapes | Brush · Arrow · Rectangle · Path · Ellipse |
| Annotations | Text · Note |

Select a drawing to move it, change its color, **line width and style** or delete it. The **Undo** button takes back up to 30 steps.

### 🔔 Alerts
- Create a price alert from the crosshair **"+"** or from the **Alerts** manager
- Alert line on the chart: tap it to delete it
- Active / inactive list, cancel and delete
- **Push notifications even when the app is closed** (can be turned off in Profile › Notifications)

### ⏪ Bar Replay
- Place a **guide line** on the exact candle you want and start from there
- Play at 1x–10x speed or step one candle at a time — perfect for backtesting

### 🧭 Chart Hub
| Section | What it does |
|---|---|
| **Layouts** | New · Save · Open your saved chart setups |
| **Chart** | Chart type, chart settings, canvas, symbol details |
| **Analysis** | Compare · Bar Replay · Alerts · Technicals · Script editor |
| **Technicals** | Buy/sell gauge from oscillators and moving averages |
| **Share** | Creates an image of your chart and opens the share sheet |

### 👤 Profile & settings
- Theme (dark/light), language and notifications
- Feedback form to report a problem or suggest an idea
- Refresh data, safe reset, sign out

---

## 📲 Installation

> 🌐 The app lives at **[nexuscharts.app](https://nexuscharts.app)**.

> NexusCharts is installed from the browser — no App Store or Play Store needed.

### 🍎 iPhone (Safari)
1. Open the NexusCharts link in **Safari**.
2. Tap **Share** (the square with the arrow). On iOS 26 tap the **three dots ⋯** first, then **Share**.
3. Tap **Add to Home Screen** (if you don't see it, tap **View More**).
4. Keep **Open as Web App** on, check the name is **NexusCharts**, tap **Add**.
5. Open **NexusCharts** from your Home Screen.

### 🤖 Android (Chrome)
1. Open the NexusCharts link in **Chrome**.
2. Tap the **three dots ⋮** at the top right.
3. Tap **Install app** (or **Add to Home screen**) and confirm.

### 💻 Desktop (Chrome / Edge)
1. Open the NexusCharts link.
2. Click the **install icon** in the address bar, or open it in a normal tab.

> 💡 The same guide is available inside the app: tap **Install** at the top right of the sign-in screen (it appears only when the app is opened from the browser).

---

## 🔑 How to get access

1. Open **[nexuscharts.app](https://nexuscharts.app)** and tap **Create an account**.
2. Pick a username, email and password, and confirm you are 18 or older and have read the Privacy Policy.
3. Enter the 6-digit code sent by email and you're in.

From then on the app signs you in by itself. On a new phone just sign in with your username or email and password.

Have a **friend code**? Tap **Use a code** and type it (format `XXXX-XXXX`): it works on one device only.

> 💬 Need help? Write to **support@nexuscharts.app**.

---

## ✅ Compatibility

| Device | Browser | Status |
|---|---|---|
| iPhone (iOS 16.4 or later) | Safari | ✅ Recommended |
| iPhone | Chrome / Edge | ✅ Works (install via Share) |
| Android 10 or later | Chrome | ✅ Supported |
| Android | Samsung Internet / Edge | ✅ Works |
| iPad | Safari | ⚠️ Works, designed for phones |
| Desktop | Chrome / Edge / Safari | ⚠️ Works, full desktop version coming |

**Requirements:** an internet connection. Push notifications on iPhone need the app installed on the Home Screen.

---

## 🔒 Privacy & security

- 👤 An account needs only a **username, email and password**. We never see your password: the server keeps only an encrypted fingerprint of it.
- 📜 All the details are in the **[Privacy Policy](https://nexuscharts.app/privacy.html)**.
- 📱 Drawings, layouts, indicators, scripts and settings are saved **only on your device**.
- 📡 The data server stores only market prices: no IP addresses and no personal data.
- 🔔 If you turn on notifications, your active price alerts are kept on the server only to notify you; delete an alert and it's gone.
- 🔐 No passwords or private keys are stored in this repository.
- 🎟️ Access codes are tied to a single device and can be revoked at any time.
- 🛡️ **Protection against code guessing**: after too many wrong codes from the same network, sign-in pauses for a while and the app shows a clear message. Valid codes and linked devices are never affected.
- 🧹 **Reset app** erases everything saved on the device.

---

## 🏗️ How it's built

- 🖥️ **The app** (what you see on your screen) lives in this repository and is published as a web app.
- ⚙️ **The engine** runs on Cloudflare: an **account server** (sign-up, sign-in, emails), a **data server** that streams live prices and keeps the candle history, and a server for friend codes and alerts. They are managed separately and are not part of this repository.
- 🔐 Keys and passwords live only in the engine's encrypted settings, never in the code.

---

## 🔢 Versioning

Versions use three numbers, **MAJOR.MINOR.PATCH** (for example 0.43.0):

- **First number**: big changes.
- **Middle number**: new features.
- **Last number**: fixes and improvements.

---

## ❓ FAQ

<details>
<summary><b>Do I need to pay or subscribe?</b></summary>
No. Installing and using NexusCharts is free — you only need an access code.
</details>

<details>
<summary><b>Do I need a broker account?</b></summary>
No. With an access code you sign in without any broker registration.
</details>

<details>
<summary><b>Can I trade from the app?</b></summary>
No. NexusCharts is for charts and analysis only — it never places orders.
</details>

<details>
<summary><b>Can I use my own Pine Script™ indicators?</b></summary>
Yes. Paste your script in the Script editor, save it and add it from My scripts. Most v5/v6 features are supported; if something isn't, the console tells you the line.
</details>

<details>
<summary><b>Do price alerts work when the app is closed?</b></summary>
Yes, with push notifications on. On iPhone the app must be installed on the Home Screen.
</details>

<details>
<summary><b>My code says it's already used on another device.</b></summary>
Each code works on one device only. Ask for a new one on Telegram.
</details>

<details>
<summary><b>Do I need to update the app?</b></summary>
No. It updates itself every time you open it.
</details>

<details>
<summary><b>Do my drawings and indicators sync between devices?</b></summary>
Not yet: they're saved on the device where you made them.
</details>

---

## 🗺️ Roadmap

| Status | Feature |
|---|---|
| ✅ | Watchlist, live chart, timeframes, chart types, custom colors |
| ✅ | Drawing tools, Bar Replay, Chart Hub, layouts |
| ✅ | 42 built-in indicators, favorites, indicator settings |
| ✅ | Pine Script™-compatible engine and script editor |
| ✅ | Price alerts with push notifications |
| ✅ | 5 languages (German added in 0.44.0), dark and light theme |
| ✅ | Design 3.0: welcome screens, logo animation, orbit language menu |
| ✅ | Design 3.0 sign-in: orbit logo, 8-box access code, round flags |
| ✅ | Design 3.0 inside the app, multiple watchlists, Signals, drawing width/style and Undo |
| ✅ | Our own data server: live streaming, 72 instruments, names in 5 languages |
| ✅ | NexusCharts accounts, new address nexuscharts.app, Privacy Policy |
| 🔜 | Longer candle history (years) |
| 🔜 | Stocks |
| 🔜 | Full desktop version |
| 💡 | Sync between devices |

---

## 🙏 Credits

- Charts powered by [TradingView Lightweight Charts™](https://www.tradingview.com/lightweight-charts/) (Apache 2.0).
- Market data from [biquote.io](https://biquote.io). Prices are for analysis and may differ from your broker's.
- Crypto icons from [cryptocurrency-icons](https://github.com/spothq/cryptocurrency-icons) (CC0 1.0).
- TradingView and Pine Script are trademarks of TradingView, Inc. NexusCharts is not affiliated with TradingView.

---

## ⚠️ Disclaimer

NexusCharts is an analysis tool. Nothing in the app is financial advice. Trading involves risk: always do your own research.

<div align="center">

**© 2026 NexusCharts — All rights reserved.**

</div>
