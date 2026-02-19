# 🕷️ Telegram AI Assistant (Spider-Style Persona)

An n8n workflow that connects Telegram with OpenAI (GPT-5-mini) to create a witty, Spider-Man–style AI assistant.

The bot:
- Replies in a witty, heroic tone
- Refines user prompts
- Sends responses directly back to Telegram

---

## 🚀 How It Works

1. Telegram Trigger  
   Listens for incoming Telegram messages.

2. AI Agent (OpenAI GPT-5-mini)  
   - Uses a predefined system prompt.
   - Responds in Spider-Man style.
   - Refines user prompts for clarity and strength.

3. Telegram Node  
   Sends the AI response back to the user.

---

## 🧠 Features

- Personality-driven responses
- Prompt refinement
- Real-time Telegram interaction
- Clean response delivery

---

## 🔧 Setup Instructions

1. Import the JSON file into n8n.
2. Add credentials:
   - Telegram Bot API
   - OpenAI API Key
3. Activate the workflow.
4. Start chatting with your Telegram bot.

---

## 🛠 Requirements

- n8n (latest version)
- Telegram Bot Token
- OpenAI API Key

---

## 📦 Architecture

Telegram → AI Agent → Telegram

---

## 📄 License

Personal / Educational use.

# 📧 Telegram AI Email Assistant (n8n + Gmail + OpenAI)

An AI-powered email assistant built using n8n, Telegram, OpenAI GPT-5-mini, and Gmail.

This assistant can:
- Summarize emails
- Send emails
- Summarize and send emails
- Return a structured execution report

---

## 🚀 Workflow Overview

1. Telegram Trigger  
   Receives user commands.

2. AI Agent (GPT-5-mini)  
   - Interprets the request.
   - Decides the correct action.
   - Returns a strict execution report.

3. Gmail Tools  
   - Fetch emails
   - Send emails

4. Telegram Response  
   Sends execution report back to user.

---

## 📋 Output Format (Strict)

Task Performed:  
Email Summary / Email Sent / Email Summary & Sent  

Details:  
- If summarized → confirms summary  
- If sent → shows recipient  
- If both → confirms both  

Status:  
Success  

Rules:
- No greetings
- No reasoning
- No email body unless requested

---

## 🧠 Example Commands

- Summarize my latest email
- Send an email to john@example.com about tomorrow’s meeting
- Summarize the last email and send it to my manager

---

## 🔧 Setup Instructions

1. Import workflow JSON into n8n.
2. Connect:
   - Telegram API
   - OpenAI API
   - Gmail OAuth2
3. Activate workflow.
4. Use via Telegram.

---

## 🛠 Requirements

- n8n
- Telegram Bot Token
- OpenAI API Key
- Gmail OAuth2 credentials

---

## 📦 Architecture

Telegram → AI Agent → Gmail Tool(s) → Telegram

---

## 📄 License

For personal and educational use.
