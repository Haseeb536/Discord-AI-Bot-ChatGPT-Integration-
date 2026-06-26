# 🤖 Discord AI Bot – ChatGPT Integration

A powerful Discord bot built with Python, `discord.py`, and OpenAI's ChatGPT API that enables dynamic chat and image generation directly in your Discord servers. Supports custom commands, multi‑modal responses, and is modularly designed for scalable integration with future OpenAI or Discord features.[reference:0][reference:1]

---

## ✨ Features

- **💬 Dynamic Chat** – Responds to user messages using OpenAI's ChatGPT API (GPT‑3.5 / GPT‑4).
- **🖼️ Image Generation** – Generate images via AI (powered by `g4f` and OpenAI integrations).
- **🎮 Custom Commands** – Easily extend the bot with your own slash commands or prefix‑based commands.
- **📁 Modular Architecture** – Clean separation of concerns; the bot logic is organised in a `src` package for maintainability and future expansion.
- **🔐 Secure Credential Management** – Uses `python-dotenv` to keep API keys and tokens out of your code.
- **🌐 Multi‑Modal Responses** – Supports text, images, and rich embeds.
- **🧠 Configurable System Prompt** – Customise the bot's personality via an external `system_prompt.txt` file.
- **⚡ Lightweight & Fast** – Built with performance in mind; minimal overhead for quick responses.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python** (3.8+) | Core programming language |
| **discord.py** (2.3.2) | Discord API wrapper for handling events, commands, and interactions[reference:2] |
| **OpenAI** (1.30.3) | Official OpenAI Python client for ChatGPT API[reference:3] |
| **g4f** (0.3.2.2) | Unofficial library for accessing various AI models (including image generation)[reference:4] |
| **Selenium** (4.9.1) | Browser automation for advanced web interactions[reference:5] |
| **python-dotenv** (1.0.0) | Load environment variables from `.env` file[reference:6] |
| **asgiref** (3.6.0) | ASGI compatibility layer[reference:7] |


