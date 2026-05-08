# DEPHINE-MD 🌸

> Elegant WhatsApp Bot — Powered by Boycoe Dev  
> Built on [@whiskeysockets/baileys](https://github.com/whiskeysockets/baileys)

---

## Features

- 234+ commands across 22 plugin categories
- AI: GPT-4, DALL-E, Gemini image generation
- Group management: ban, promote, mute, lock, welcome, goodbye
- GcStatus: per-group status with image/video, scheduled announcements
- Downloaders: YouTube (audio + video), TikTok, Instagram, Facebook
- Fun/love/design/dev commands
- Polls, scheduler, triggers, social (XP, AFK, reputation)
- All messages forwarded from the official channel
- Auto-status view, auto-react, auto-typing indicators

---

## Setup

### 1. Clone & install
```bash
git clone <your-repo-url>
cd DEPHINE-MD/bot
npm install
```

### 2. Configure
Copy `.env.example` to `.env` and fill in:
```env
BOT_NAME=DEPHINE-MD
PREFIX=.
OWNER_NUMBER=263781021754   # your number (no + or spaces)
BOT_NUMBER=263781021754     # number to pair the bot with
OPENAI_KEY=sk-...           # OpenAI API key
GEMINI_KEY=AIza...          # Google Gemini API key
```

### 3. Run
```bash
node index.js
```

On first run you will see a **pairing code** in the terminal.

**On the bot phone:**
1. WhatsApp → ⋮ → Linked Devices → Link a Device
2. Tap **"Link with phone number"** (bottom of QR screen)
3. Enter the 8-character code shown in the terminal

---

## Commands (prefix: `.`)

| Category | Commands |
|----------|----------|
| AI | `.gpt`, `.gemini`, `.imagine`, `.dalle` |
| Group | `.ban`, `.promote`, `.demote`, `.mute`, `.lockgroup` |
| GcStatus | `.gcstatus set/get/clear/welcome/goodbye/announce` |
| Downloader | `.play`, `.video`, `.tiktok`, `.instagram` |
| Fun | `.joke`, `.dice`, `.8ball`, `.truth`, `.dare` |
| Social | `.level`, `.rank`, `.afk`, `.rep` |
| Polls | `.poll`, `.vote`, `.endpoll` |
| Search | `.google`, `.wiki`, `.weather`, `.news` |
| Owner | `.broadcast`, `.eval`, `.restart`, `.setprefix` |

Type `.menu` in WhatsApp for the full command list.

---

## Join our channel for updates 

All updates from:  
**https://whatsapp.com/channel/0029VbBxPYN2kNFj3I1H1e0f**

---

## Owner
**Boycoe** — +263781021754

---

## License
MIT

