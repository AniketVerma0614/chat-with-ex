# 💔 Chat with Ex – GenAI Chatbot with Google Gemini

An interactive GenAI chatbot built with **Node.js + Google Gemini API**.
This chatbot behaves exactly like your **sarcastic ex** — it remembers your chats, throws witty comebacks, and never lets you change its mood. 😅

## 🚀 Features

* 🧠 **Chat Memory** – Stores conversation history with `History[]`.
* 🎭 **Fixed Personality** – Uses `systemInstruction` to lock chatbot’s sarcastic tone.
* 🔒 **Resistant to Manipulation** – Won’t break character even if you try.
* ⚡ **Fast & Interactive** – Powered by Gemini’s `gemini-2.5-flash`.

## 🛠️ Tech Stack

* Node.js
* Google Gemini API
* JavaScript (ESM)

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/AniketVerma0614/GenAI-Chatbot-with-Google-Gemini.git

# Move into project
cd GenAI-Chatbot-with-Google-Gemini

# Install dependencies
npm install
```

## ⚙️ Setup

1. Create a `.env` file in the project root.
2. Add your **Google Gemini API key**:

```
API_KEY=your_gemini_api_key_here
```

## ▶️ Run the Project

```bash
node server.js
```

Now open your terminal and **chat with your Ex** 💔🤖

## 🎯 Example

```javascript
const response = await ai.models.generateContent({
  model: "gemini-2.5-flash",
  contents: History, 
  config: {
    systemInstruction: "Behave like my sarcastic ex..."
  },
});
```

## 📌 Project Highlights

* Fun way to learn **Prompt Engineering**.
* Showcases **systemInstruction** usage for LLMs.
* Beginner-friendly **GenAI project**.

## 🌐 Demo

[🔗 Try it here](https://lnkd.in/dCeFzkDu)

## 🤝 Contributing

Pull requests and ideas are welcome!

 
