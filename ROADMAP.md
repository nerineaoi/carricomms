# 🌟 CarriComms – Public Roadmap

This roadmap outlines the planned evolution of CarriComms from a simple multi-platform chat relay into a powerful, AI-assisted streaming companion.  
All items listed here are *safe* for public visibility and do not reveal proprietary implementation details.

CarriComms will evolve in three major phases:

- **v1.0 – Chat Relay (Current Focus)**
- **v2.0 – AI Assistant / Auto-Mod**
- **v3.0 – Cross-Platform Moderation & 2-Way Interaction**

Each version builds on the previous one while keeping the complexity manageable and ensuring earlier releases ship quickly.

---

# ✅ **v1.0 – Multi-Platform Chat Relay (MVP)**  
**Goal:** Provide a clean, unified way for streamers to view Twitch, Kick, and YouTube chat inside Discord.

### ✔ Core Features
- Unified webhook output  
- One CarriComms bot for all platforms  
- Platform-tagged messages:  
  - `[Twitch] **user**: message`  
  - `[Kick] **user**: message`  
  - `[YouTube] **user**: message`  
- Local relay (no cloud dependency)  
- Configurable `.env` with single webhook  
- Silent background execution  
- Splash screen & app launcher  
- PyInstaller distribution  

### 🛠 Planned Enhancements
- Simple configuration UI  
- Platform toggles (enable/disable Twitch/Kick/YouTube)  
- Basic logging  
- Installer packages (Win/Mac/Linux)  
- Error notifications inside Discord (optional)  
- Basic analytics (message counts, relay health)

---

# 🤖 **v2.0 – AI Assistant / Auto-Mod (Pro Tier)**  
**Goal:** Provide streamers—especially small or solo creators—with an automated assistant that analyzes chat and provides intelligent support.

### ✔ AI Assistant Functions (Read-Only / Advisory Mode)
- Chat sentiment analysis  
- Spam/bot pattern detection  
- Highlighting repeated questions  
- Identification of problem messages  
- Summaries of recent chat activity  
- Suggested replies for streamer or mods  
- “Important message” tagging  
- Behind-the-scenes auto-responses (Discord-side only)  

### ✔ Platform-Native Bot (No 2-Way Needed Yet)
CarriComms will include an optional companion bot account (“CarriBot”) for:
- Sending auto-mod warnings  
- Answering common questions  
- Triggering routine commands  
- Supporting streamers who have *no mods at all*

**Note:**  
These features operate natively *on* each platform’s chat (Twitch/Kick/YouTube) using a dedicated bot account — *not* via Discord bridge.

---

# 🛡 **v3.0 – Cross-Platform Moderation & 2-Way Interaction (Advanced)**  
**Goal:** Support larger communities and mod teams with full interaction tools.

### ✔ Moderation Tools
- CarriBot with moderator permissions on Twitch/Kick/YouTube  
- Real-time automated mod actions: timeouts, warnings, message deletion  
- Cross-platform moderation mirroring  
- Rule presets & customizable filters  

### ✔ Human Interaction Tools
- Optional 2-way chat bridging (mods reply from Discord → message appears on platform)  
- Discord slash commands for mod actions  
- Cross-platform announcements  
- Priority question queue  
- Mod dashboards & monitoring tools  

### ✔ Premium AI Enhancements
- AI-generated moderation decisions  
- Toxicity scoring  
- Viewer profiling (returning users, first-timers)  
- Smart “probation mode” for suspicious accounts  

---

# 📌 **Non-Versioned Future Ideas**
These may land in any post-v1 release depending on complexity and demand:

- Web UI dashboard for remote management  
- Log viewer with filtering & search  
- Multi-webhook support  
- Custom bot branding for subscribers  
- Advanced analytics (viewer activity heatmaps, Q&A stats)  
- YouTube Live fallback detection  
- Mobile companion app  
- Mixer-style merged chat UI (Discord overlay optional)

---

# 📬 **Progress Tracking**
Major releases and milestones will be updated here.  
For day-to-day development, see commit history and issue tracking.

---

# 💙 **Community Feedback**
If you'd like to request a feature or suggest improvements, feel free to open an Issue on GitHub or contact through Discord.

CarriComms is built to evolve — this roadmap will grow with it.
