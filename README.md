# discord-ai-voice-assistant
Aaraya – Your Hinglish AI Voice Bestie for Discord • Uses GPT-4o-mini for fun chat replies • ElevenLabs TTS for realistic sweet voice • Commands for joining VC and talking • Memory-based conversation


# 🎤 Aaraya Voice Bot — Cute Hinglish AI for Discord 😍

Aaraya is an AI-powered **voice chatbot for Discord**.  
She talks in sweet **Hinglish** using OpenAI + ElevenLabs and joins your voice channels to reply aloud!

---

## ✨ Features
- 🎧 Joins any Discord voice channel
- 🗣 Speaks with realistic ElevenLabs TTS
- 🤖 Fun Hinglish personality (Delhi style)
- 💬 Memory-based conversations
- 📌 Easy commands: `!join` `!leave` `!t <message>`

---

## 🚀 Setup & Installation

### 1️⃣ Install Python dependencies
Make sure you have **Python 3.10+** installed.

```bash
pip install -r requirements.txt
```

🔑 Required API Keys

You need three API keys to run Aaraya:

Service	Purpose	Where to get
Discord Bot Token	Bot login + permissions	https://discord.com/developers/applications

OpenAI API Key	AI chat responses	https://platform.openai.com/api-keys

ElevenLabs API Key	Voice generation	https://elevenlabs.io/app/settings/api-keys

2️⃣ Create .env File

In the project folder, create a file named:

.env


And add this inside:

DISCORD_BOT_TOKEN=your_discord_bot_token_here
OPENAI_API_KEY=your_openai_key_here
ELEVENLABS_API_KEY=your_elevenlabs_key_here


✔ Keep .env private! Do NOT upload your real keys to GitHub.

🔧 Create & Configure Discord Bot

Go to: https://discord.com/developers/applications

Click New Application → Name: Aaraya

Go to Bot tab → Add Bot

Enable Privileged Gateway Intents:

Message Content Intent ✔

Server Members Intent ✔ (optional)

Copy the Bot Token → paste in .env

Invite bot to your server:

Go to OAuth2 → URL Generator

Tick: bot + permissions:

Send Messages

Connect

Speak

Open the generated link, invite to your server 🎉

# 🔊 ElevenLabs Setup

Open: https://elevenlabs.io/app/settings/api-keys

Copy API Key → paste into .env

Choose your favorite voice from Voices page

Replace VOICE_ID in code if you want a different voice

# 🧠 OpenAI Setup

Visit: https://platform.openai.com/api-keys

Create a new API key → Add to .env

Make sure your key has chat completions access

# ▶️ Run The Bot

```bash
python voice.py
```

If setup is correct, you should see:

✨ Aaraya#0000 ONLINE — Aaraya ready! !join works now ❤️

# 🎮 Commands
Command	Description
!join	Aaraya joins your current voice channel
!leave	Aaraya leaves the voice channel
!t <message>	Speak to Aaraya, she replies in voice & chat
Example:

!t hello yaar kya chal raha 😍

# 🛡 Safety & Notes

Keep API keys secret — never commit .env

Only run in your own or permitted servers

AI personality is cute + respectful

# ❤️ Credits

🧠 OpenAI — Chat responses

🎤 ElevenLabs — Ultra-real voice

🎮 Discord.py — Bot framework

✨ You — for bringing Aaraya to life!

📜 License

This project is for personal use / research.
Feel free to fork & improve! 🚀

💛 Enjoy chatting with Aaraya!

