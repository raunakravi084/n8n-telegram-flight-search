# ✈️ Telegram AI Flight Search Bot (n8n + Amadeus)

An AI-powered Telegram bot built with **n8n**, **Amadeus APIs**, and **LLMs** that lets users search for flights using natural language.

Example:
> "Find me a flight from Delhi to Mumbai next Friday"

---

## 🚀 Features
- Telegram chatbot interface
- Natural language flight queries
- AI-powered intent & parameter extraction
- Real-time flight search via Amadeus
- Richly formatted Telegram responses
- Secure credential handling (no secrets in repo)

---

## 🧱 Tech Stack
- n8n
- Telegram Bot API
- Amadeus Flight Offers API
- OpenAI / LLM (via n8n AI Agent)


## 🧠 **Architecture Flow**
User (Telegram)
      ↓
Telegram Bot API
      ↓
n8n Telegram Trigger
      ↓
AI Intent Parser (LLM)
      ↓
Parameter Validation
      ↓
Amadeus Flight Offers API
      ↓
Response Formatter
      ↓
Telegram Message

---


## 🖼️ Workflow Overview

<img width="1712" height="490" alt="image" src="https://github.com/user-attachments/assets/d8dfcf42-301a-4ae6-b66d-9d81315511ff" />

## 💬 Telegram Bot Example

<img width="1352" height="756" alt="image" src="https://github.com/user-attachments/assets/411088e7-6973-4628-9295-127d23f1342b" />



## 🧪 Example Queries

"Flight from Bangalore to Dubai on 15 Oct"

"Round trip Delhi to Mumbai next week"

"Need cheapest flight from London to Paris tomorrow"
