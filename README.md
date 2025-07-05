# AnioSEC 🔒

**An advanced, open-source Discord moderation bot** designed to keep your server secure and well-managed. Developed with ❤️ by [neronx1234](https://github.com/neronx1234).

![Discord](https://img.shields.io/discord/wTWYZtZw89?label=Support%20Server&style=flat-square) 
![GitHub stars](https://img.shields.io/github/stars/Aniosssz/AnioSEC?style=flat-square)
![License](https://img.shields.io/github/license/Aniosssz/AnioSEC?style=flat-square)

---

## 🌟 Features

### 🛡️ Moderation
- Kick/Ban/Mute/Timeout with customizable reasons
- Auto-moderation (anti-spam, anti-mass-mention)
- Role management

### 📜 Logging
- Channel-specific logs (joins, leaves, deletions)
- Moderation action tracking

### 💣 Anti-Nuke Protection
- Role/Channel creation/deletion rate-limiting
- Admin abuse prevention

### 🔐 Privacy-Focused
- GDPR-compliant data handling
- Zero third-party data sharing
- Self-hostable (full control over data)

### 🔌 Extensible
- Modular design (easy to add new features)
- Support for custom plugins

---

## 🚀 Quick Start

### Prerequisites
- Node.js v18+ ([Download](https://nodejs.org))
- Git (optional, for developers)

### Installation
```bash
# Clone the repository
git clone https://github.com/Aniosssz/AnioSEC.git
cd AnioSEC

# Install dependencies
npm install
```
Setup the environment
```env
DISCORD_TOKEN=your_bot_token_here
SUPABASE_URL=your_supabase_url
SUPABASE_ANON_KEY=your_anon_key
```
Then, run the bot!
```bash
npm start
```
