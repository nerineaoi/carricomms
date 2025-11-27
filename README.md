# **CarriComms**
### *Cross-platform chat relay for streamers.*

![Status](https://img.shields.io/badge/status-in_development-orange)
![License](https://img.shields.io/badge/license-Apache%202.0-blue)
![Platforms](https://img.shields.io/badge/platforms-Twitch%20%7C%20YouTube%20%7C%20Kick%20%7C%20Discord-purple)

> **CarriComms = carry your comms — not your games.**  
Now with a destiny-worthy upgrade:  
**One hub to sync all chats.**
---

![CarriComms Overview](./docs/overview.png)

## 🚀 What is CarriComms?
CarriComms is a lightweight, CPU‑friendly, multi‑platform stream companion that unifies chat from **Twitch**, **YouTube**, and **Kick** into a single clean interface — plus notifications, supporter tracking, and basic moderation tools.

No tab chaos.  
No missing messages.  
No stress.

Just **your stream**, simplified.

---

## ✨ Core Features

### **Unified Chat Panel**
- Twitch, Kick, YouTube (supported events)
- Real‑time only (no long‑term logs)
- Clean, readable formatting  
- Zero clutter, zero distractions

### **Supporter Inbox**
A specialized inbox for **paid events**:
- bits / cheers  
- tips  
- gift subs  
- SuperChats (when supported)  
Includes:
- read/unread  
- filters (min amount)  
- sorting (amount/time)  
- retention window (1–14 days)  
- archive  
- auto‑cleanup  

### **Notifications**
- Optional toast pop‑ups  
- Optional sound alerts  
- Toggle per event type  
- Extremely light on CPU  

### **Moderation Tools**
- Blocked‑word list  
- Basic caps/spam detection  
- Temporary flagged‑message storage  

---

## 🛠 Tech Stack
- **Python**
- **Tkinter** (desktop UI)
- **SQLite** (settings + paid events)
- **Official Twitch / Kick / YouTube APIs**

All implementation code lives in a **private repository** for IP protection.

---

## 📁 Public Repository Structure

```
CarriComms-Public/
│
├── README.md
├── roadmap.md
│
├── branding/
│   ├── logo.png
│   └── overview.png
│
├── screenshots/
│   ├── ui-mockups/
│   └── concepts/
│
├── media/
│   ├── banners/
│   └── promos/
│
└── TFG/
    ├── memoria.md
    ├── requisitos.md
    └── entregables/
```

All technical implementation details remain private.

---

## 🛠 Status
🟩 **In active development (private repo)**  
🟧 **Public docs & branding available here**  
🟥 **Core code unreleased**

---

## 🔐 Security
- No passwords stored  
- OAuth2 only  
- No analytics  
- No tracking  
- No invasive logging  
- User tokens encrypted  

CarriComms handles **only** what the APIs allow safely.

Full security documentation will be added at release.

---

## 📚 Documentation
- System overview (`/docs/overview.png`)
- Relay flow (`/docs/flow-diagram.png`)
- Basic setup guide (coming soon)

---

## 🛣 Public Roadmap 
See 👉 [ROADMAP.md](./ROADMAP.md)
---

## 📝 License
**Apache License 2.0**  
See `LICENSE` for details.

CarriComms © 2025 **Nerine Aoi** *(byneriaoi)*
