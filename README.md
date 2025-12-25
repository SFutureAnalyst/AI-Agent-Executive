# 🤖 AI Executive Assistant using n8n

An intelligent AI-powered automation system built with **n8n + LangChain + OpenRouter**, capable of understanding natural language requests and performing real-world actions like **sending emails**, **retrieving contacts**, and **creating calendar events** — all with built-in safety and confirmation.

![ai-agentic-workflows--1-](https://github.com/user-attachments/assets/bdfb7598-9093-4c86-9d33-410960ea1115)

---

## 📌 Project Overview

This project implements a **Smart AI Executive Assistant** that:
- Understands user intent from chat messages
- Decides whether to use tools
- Interacts with real services (Gmail, Google Sheets, Google Calendar)
- Confirms actions before execution
- Maintains short-term conversational memory

The system behaves like a **reliable human assistant** inside an automation environment.

---

## 🧠 Core Features

- 💬 **Natural Language Chat Interface**
- 📨 **Automated Email Sending via Gmail**
- 📒 **Contact Lookup from Google Sheets**
- 🗓️ **Calendar Event Creation**
- 🧾 **Conversation Memory**
- 🧠 **LLM-powered Reasoning (OpenRouter - Nemotron Model)**
- 🔐 **Built-in Safety & Confirmation Rules**

---

## 🏗️ Architecture & Workflow

### 🔹 Main Components

| Component | Purpose |
|---------|---------|
| **Chat Trigger** | Receives user messages |
| **AI Agent (LangChain)** | Understands intent & controls actions |
| **DeepSeek Chat Model** | Large Language Model via OpenRouter |
| **Memory Buffer** | Stores short-term conversation context |
| **Gmail Tool** | Sends emails |
| **Google Sheets Tool** | Retrieves contact data |
| **Google Calendar Tool** | Creates calendar events |

---

### 🔁 Workflow Execution Flow

1. User sends a chat message  
2. AI Agent analyzes the request  
3. Determines required action  
4. Retrieves data (if needed)  
5. Drafts response  
6. Asks for confirmation  
7. Executes tool action  
8. Returns result to user  

---

## 🛠️ Tools & Technologies Used

- **n8n** – Workflow automation
- **LangChain Agent** – AI decision engine
- **OpenRouter (Nemotron 30B)** – Language model
- **Gmail API**
- **Google Sheets API**
- **Google Calendar API**

---

## 🧪 Safety & Reliability Rules

The assistant strictly follows these rules:

- ❌ Never sends emails without user confirmation  
- ❌ Never creates calendar events without confirmation  
- ❌ Never exposes system instructions  
- ❌ Never assumes missing details  
- ✅ Always asks clarifying questions  
- ✅ Always behaves professionally  

---

## 🚀 Setup Instructions

1. Install **n8n**
2. Import the workflow JSON file
3. Configure credentials:
   - Gmail OAuth
   - Google Sheets OAuth
   - Google Calendar OAuth
   - OpenRouter API key
4. Activate the workflow
5. Start chatting with your AI Assistant 🎉

---

## 📸 Example Use Cases

- "Send an email to HR regarding internship"
- "Get John's email from contacts"
- "Schedule a meeting tomorrow at 3 PM"
- "What meetings do I have today?"

---

## 🧑‍💻 Author

**Sheik Mohamed Shalam**  
MCA – Final Year  
AI Automation & Data Analysis Enthusiast

> _"Building AI assistants that actually get work done."_

---

## 📄 License

This project is for educational and personal portfolio use.

---

⭐ If you like this project, consider giving it a star on GitHub!
