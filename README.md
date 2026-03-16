# Synthora Assistant: WhatsApp AI Workflow for n8n

This repository contains the official **n8n workflow** for Synthora, an AI personal assistant that lives in your WhatsApp.

## 🤖 What is Synthora?
Synthora is a sophisticated **n8n workflow** that uses LangChain and Groq (Llama 3.1) to create an omnipresent assistant. By simply chatting on WhatsApp, you can:
- 📅 Manage your **Google Calendar**.
- 📧 Search and summarize your **Gmail**.
- 📞 Manage **Google Contacts**.
- 📊 Log ideas to **Google Sheets**.
- 📺 Search for tech tutorials on **YouTube**.

## 📦 How to use this workflow

1.  **Download the JSON**: Grab the [synthora-assistant.json](workflows/synthora-assistant.json) file from this repository.
2.  **Import to n8n**:
    - Open your n8n instance.
    - Go to **Workflows > Import from File**.
    - Select the JSON file you downloaded.
3.  **Requirements**:
    - An n8n instance.
    - WhatsApp Business API credentials.
    - Google Cloud Console access (for Gmail/Calendar/Contacts).
    - A Groq API Key (or any other LLM provider).

## 📄 License
This workflow is shared under the Apache License 2.0.

---
*Shared by Senan.*
