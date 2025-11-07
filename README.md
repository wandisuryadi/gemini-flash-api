# 🚀 Gemini Flash API

A simple Express.js API that generates text using **Google Gemini AI (Generative Language API)**.  
This project demonstrates how to build a RESTful endpoint to handle text generation prompts and return AI-generated responses in JSON format.

---

## 📦 Features

- 🧠 Uses **Gemini AI (Google Generative AI)** for text generation  
- ⚡ Simple **/generate-text** POST endpoint  
- 🛡️ Secure with `.env` API key configuration  

---

## 🧩 Requirements

Make sure you have installed:

- [Node.js](https://nodejs.org/) v18 or later  
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)  
- A valid **Google Gemini API key** from [Google AI Studio](https://aistudio.google.com/app/apikey)

---

## ⚙️ Installation

Clone this repository:

# 1️⃣ Clone the repository
git clone https://github.com/yourusername/gemini-flash-api.git

# 2️⃣ Enter the project directory
cd gemini-flash-api

# 3️⃣ Install all dependencies
npm install express dotenv cors @google/genai

# 4️⃣ Create an environment file
cp .env.example .env

# 5️⃣ Start the server
npm index.js