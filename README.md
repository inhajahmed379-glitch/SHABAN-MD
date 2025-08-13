minhaj-bot/
├─ package.json
├─ index.js
├─ .env.example
├─ commands/
│  ├─ help.js
│  ├─ ping.js
│  ├─ alive.js
│  ├─ tts.js
│  ├─ sticker.js
│  ├─ tagall.js
│  └─ gpt.js
└─ utils/
   ├─ ai.js
   └─ files.{
  "name": "minhaj-bot",
  "version": "2.0.0",
  "description": "WhatsApp bot (Baileys) – Minhaj Bot",
  "type": "module",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "dependencies": {
    "@whiskeysockets/baileys": "^6.7.8",
    "axios": "^1.7.2",
    "dotenv": "^16.4.5",
    "fs-extra": "^11.2.0",
    "google-tts-api": "^2.0.1",
    "openai": "^4.56.0",
    "pino": "^9.0.0",
    "qrcode-terminal": "^0.12.0",
    "sharp": "^0.33.4"
  }
# তোমার বটের নাম
BOT_NAME=Minhaj Bot

# Owner নম্বর (দেশ কোড ছাড়া কোনো + সাইন নয়); BD হলে 880 দিয়ে শুরু
OWNER_NUMBER=8801834737430

# কমান্ড প্রিফিক্স
PREFIX=.

# সেশন/অথ ফোল্ডার (Railway Volume হলে /data ব্যবহার করো)
SESSION_DIR=./session

# OpenAI চাইলে সেট করো, নইলে ফাঁকা রাখো
OPENAI_API_KEY=
