# AnioSEC

A powerful and open-source moderation bot for Discord servers, built and maintained by neronx1234.

---

## ✨ Features

- Advanced moderation (kick, ban, mute, timeout, etc.)
- Logging system 
- Anti-nuke system
- Unlockable features
- GDPR-compliant and secure
- No data-sharing with 3rd Party Apps
- and more features!

---

## 🛠️ Installation

### Prerequisites

1. Download [Node.js](https://nodejs.org/en/download) (LTS recommended but you can install newest versions too.)
2. (Optional - Recommended for Developers) Download [Git](https://git-scm.com/downloads)

### Installation for Beginners

```bash
npm install
```


### Installation for Developers (Using Git)

```bash
git clone https://github.com/Aniosssz/AnioSEC.git
cd AnioSEC
npm install
```

### Creating .env File
Create a .env file in the root directory and add the following:
```env
DISCORD_TOKEN=your_bot_token
SUPABASE_URL=your_url
SUPABASE_ANON_KEY=your_anon_key
```
Then start the bot by running "npm run start"

## Bot Permissions

### Bot Permissions
Make sure your bot has the Administrator permission and drag the bot's role above all roles.
It's required for preventing Admin Abuse.

### Privileged Gateway Intents
Make sure to enable following Discord Bot Intents =
- Server Members Intent
- Message Content Intent
- Presence Intent

## How to Get Supabase Key and URL
1. Go to the [supabase.com](https://supabase.com/) and create an account.
2. Create a project and name it whatever you want.
3. Then open the project and go to the Project Settings
4. Go to the API Keys and copy the anon public key. 
5. Then go to the Data API and copy the Project URL

## Hosting

### Your Own Computer (Not Recommended)

If you want your bot to be active 24/7, using your own personal computer does not make sense because you will have to keep your computer on all the time and it will also slow down your computer's performance.
However, if you still want to host the bot on your own computer, just follow the steps above and keep CMD or Terminal open.

### VDS / Glitch

You can rent a VDS from a service provider like Hostinger, it costs money but most providers provide 99% 24/7 uptime.

You can import this project from Glitch and start your bot by doing the same steps in Glitch, you can access 24/7 uptime for free by registering your Glitch URL in a system like UptimeRobot. You can learn these topics more easily from YouTube.

