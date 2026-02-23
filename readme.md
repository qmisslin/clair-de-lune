# Clair de Lune

<p align="center">
  <img src="icon.svg" alt="Clair de Lune icon" width="120">
</p>

A simple, private, and local-first menstrual cycle and ovulation tracker.

🌙 Live application:  
https://qmisslin.github.io/clair-de-lune/

---

## ✨ Features

### 📅 Calendar View
- Fullscreen monthly calendar
- Always displayed on 6 rows (consistent layout)
- Current month displayed by default
- Previous and next months preloaded for smooth navigation

### ↔ Navigation
- **Mobile:** horizontal swipe (native smooth scroll behavior)
- **Desktop:** left and right arrow buttons
- Snap behavior: one month at a time

### 🎨 Visual Indicators
- 🩷 Period days (pink)
- 🟡 Fertile window (yellow)
- 🟠 Ovulation day (orange)
- Today highlighted
- Future days displayed with reduced opacity (50%)

### ⚙ Parameters
Configurable via the **Settings** panel:
- First day of last period
- Cycle length (in days)
- Period duration (in days)
- Luteal phase length

All calculations are done locally in the browser.

### 📱 Installable Web App (Android)
- Installable directly from Chrome
- Opens in standalone mode (no browser UI)
- App icon on home screen

---

## 📲 Install on Android

1. Open the live application in **Google Chrome**:
   https://qmisslin.github.io/clair-de-lune/
2. Tap the **Install (+)** button in the header  
   or use Chrome menu → **Add to Home Screen**
3. Confirm installation

The app will launch in standalone mode like a native application.

If updating the icon or manifest:
- Uninstall the app first
- Reinstall to refresh the cached icon

---

## 🔐 Privacy & Data Storage

Clair de Lune is **100% local-first**.

- No backend
- No analytics
- No cookies
- No remote database
- No cloud sync

All data is stored in your browser’s **localStorage**.

### ✅ Advantages
- Complete privacy
- No account required
- No data transmitted over the network
- Instant loading

### ⚠ Limitations
- Data is tied to the device and browser
- No automatic synchronization across devices
- Clearing browser storage will erase data
- Manual configuration required on each device

---

## 🛠 Technical Notes

- Static site (GitHub Pages)
- No external backend
- LocalStorage persistence
- PWA-capable (installable on Android)
- Pure HTML / CSS / JavaScript

---

## 📄 License

MIT License

You are free to:
- Use
- Modify
- Distribute
- Use commercially
- Fork and improve

Both personal and commercial usage are permitted under the MIT license.

---

## 🤍 Philosophy

Clair de Lune was built with a simple idea:

A cycle tracker should be private, lightweight, and fully under the user’s control.