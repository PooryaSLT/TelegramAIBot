# 🤖 AI Tools Telegram Bot

Welcome to the **AI Tools Telegram Bot**, your personal assistant for creating AI-generated art, enhancing images, and more!  
This Telegram bot leverages the power of various AI models to perform tasks like generating art from text prompts, high-resolution image restoration, colorizing black and white photos, removing backgrounds, and describing the content of images.

---

## 📋 Table of Contents
- [Features](#✨-features)  
- [Installation](#🚀-installation)  
- [Commands](#💻-commands)  
- [Contributing](#🤝-contributing)  
- [Contact](#📬-contact)  
- [License](#📄-license)  

---

## ✨ Features
- 🎨 **Create AI Art (Text To Image):** Generate stunning AI art from text prompts.  
- 🖼️ **Robust Face Restoration:** Restore old photos with advanced face restoration algorithms.  
- 🌈 **Add Colors to Old Images:** Colorize black and white photos to bring them to life.  
- 🪄 **Remove Photo Backgrounds:** Effortlessly remove backgrounds from photos.  
- 🔍 **Visual Description AI:** Get detailed descriptions of the content of images.  

---

## 🚀 Installation

1. **Install required Python libraries:**

```bash
pip install pyrogram==2.0.106 replicate asyncio requests
```

2. **Obtain API tokens:**  
- **Telegram API ID & API Hash:** from [my.telegram.org/apps](https://my.telegram.org/apps)  
- **Bot token:** from [@BotFather](https://t.me/BotFather)  
- **Replicate API token:** from [Replicate](https://replicate.com/)  

3. **Set environment variables:**

```bash
export REPLICATE_API_TOKEN="your_replicate_api_token"
```

4. **Update the API configurations** in the script with your obtained tokens.  

5. **Run the bot:**

```bash
python bot.py
```

---

## 💻 Commands

Start the bot and use the following commands to interact with it:

- `/art [prompt]` – Create AI art from a text prompt.  
- `/resolution` – Enhance the resolution of a photo (Reply to a photo).  
- `/colorize` – Add colors to a black and white photo (Reply to a photo).  
- `/removebg` – Remove the background of a photo (Reply to a photo).  
- `/describe` – Get a detailed description of the content of a photo (Reply to a photo).  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to open issues or pull requests to improve functionality or fix bugs.  

---

## 📬 Contact

<p align="center">
  <b>💡 Feel free to reach out if you have any questions or suggestions!</b>
</p>

<p align="center">
  <a href="https://t.me/LampStack">
    <img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
  <a href="mailto:xialop@outlook.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 📄 License

This project is licensed under the **MIT License**.
