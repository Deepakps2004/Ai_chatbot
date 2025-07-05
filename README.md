# 🤖 Pixel AI — Chatbot powered by Gemini API

Welcome to **Pixel AI**, a lightweight web-based chatbot interface built with HTML, CSS, JS (vanilla), and a Node.js backend. It connects to **Gemini Pro API** using your own API key to simulate AI conversations—right from your browser.

> ⚡ Built by [Deepak](https://github.com/Deepakps2004) with heart, hustle, and a touch of madness.

---

## 🚀 Features

- Sleek, Google-style branding for Pixel AI  
- Gemini API integration with fetch-based async handling  
- Real-time user & bot chat bubbles with scrollable history  
- Typing loader (using `loader.gif`)  
- Easy to extend or style — fully customizable  

---

## 🛠 Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/Deepakps2004/Ai_chatbot.git
   cd Ai_chatbot
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Add your Gemini API key**

   Create a `.env` file in the root directory and paste:

   ```env
   API_KEY="your-gemini-api-key-here"
   ```

   > 🔐 Keep your API key secret, secure, and never commit `.env` to Git.

4. **Start the server**

   ```bash
   node server.js
   ```

5. **Visit your chatbot**

   Open your browser and go to:

   ```
   http://localhost:3000
   ```

---

## 📁 Project Structure

```bash
Ai_chatbot/
├── index.html         # Frontend UI
├── server.js          # Node.js backend with Gemini API call
├── loader.gif         # Loader animation
├── package.json       # Project metadata
├── .env               # Your Gemini API key (not included in repo)
```

---

## 🧠 Powered By

- [Gemini API (Google AI Studio)](https://aistudio.google.com/)
- HTML, CSS, Bootstrap
- Node.js + Express
- Deepak's brainwaves 🧠⚡

---

## ❗ Disclaimer

Pixel AI is just a demo chatbot. While it uses LLM responses, it may **generate inaccurate or fictional responses**. Always double-check critical info.

---

## 🌟 Show some love?

If this helped you, consider starring 🌟 the repo or following me [@Deepakps2004](https://github.com/Deepakps2004). Let's build cooler stuff together 💻❤️
