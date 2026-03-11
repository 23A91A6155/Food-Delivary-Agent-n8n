# AI Chatbot using n8n, Google Gemini, and Google Sheets

This project is an AI-powered chatbot built using **n8n automation platform**, **Google Gemini AI**, and **Google Sheets** for storing FAQ data.  
The chatbot can receive messages, process them using AI, retrieve information from stored data, and provide intelligent responses.

## 🚀 Features

- AI-powered responses using **Google Gemini**
- Automated workflow built in **n8n**
- **Chat message trigger**
- **AI Agent with memory**
- Integration with **Google Sheets for FAQ retrieval**
- Dynamic response generation
- Scalable automation workflow

## 🧠 Workflow Overview

The workflow contains the following components:

1. **When Chat Message Received**
   - Trigger that activates when a user sends a message.

2. **AI Agent**
   - Processes the incoming query.
   - Uses AI reasoning to generate responses.

3. **Google Gemini Chat Model**
   - Provides intelligent natural language responses.

4. **Simple Memory**
   - Stores previous conversation context.
   - Enables better conversational experience.

5. **Google Sheets (FAQ Database)**
   - Retrieves frequently asked questions.
   - Helps provide structured responses.

6. **Items List**
   - Processes and formats retrieved data.

## ⚙️ Tech Stack

- **n8n**
- **Google Gemini AI**
- **Google Sheets API**
- **Automation Workflows**
- **AI Agent Architecture**

## 📊 Workflow Architecture

User Message  
↓  
Chat Trigger  
↓  
AI Agent  
↓  
Google Gemini Model  
↓  
Memory + Google Sheets FAQ  
↓  
Generated Response

## 🛠️ Setup Instructions

1. Install **n8n**
2. Create a new workflow
3. Add the following nodes:
   - Chat Trigger
   - AI Agent
   - Google Gemini Chat Model
   - Simple Memory
   - Google Sheets
   - Items List
4. Connect Google Sheets containing FAQ data
5. Configure Gemini API credentials
6. Activate the workflow

## 📌 Use Cases

- Customer support chatbot
- FAQ automation
- Website assistant
- WhatsApp/Chat automation
- AI support systems

## 👩‍💻 Author

**Akhila**

AI & Automation Enthusiast  
Interested in building AI-powered automation systems using modern tools.

## ⭐ Contribute

If you like this project, feel free to fork the repository and contribute.
