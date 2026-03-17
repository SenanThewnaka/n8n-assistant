# Synthora Assistant: WhatsApp AI Workflow for n8n

This is the n8n workflow for Synthora, an AI assistant that works through WhatsApp. You can use it to manage your calendar, emails, and contacts directly from your phone.

## How to use this workflow

1. Download the synthora-assistant.json file from the workflows folder.
2. Open your n8n instance and go to Workflows > Import from File.
3. Select the JSON file you just downloaded.

## Getting the required API keys

To make this workflow work, you will need to set up the following accounts and get their API keys.

### 1. WhatsApp Business API
Go to the Meta for Developers portal and create a Business App. You will need to set up the WhatsApp product to get your Phone Number ID and a temporary or permanent Access Token.

### 2. Google Cloud (Calendar, Gmail, Contacts)
Go to the Google Cloud Console and create a new project. Enable the Google Calendar API, Gmail API, and Google People API. You will need to set up OAuth2 credentials to connect these to n8n.

### 3. Groq API
Sign up at Groq Cloud to get an API key. This workflow uses the llama-3.1-8b-instant model to power the assistant's logic.

### 4. SerpApi
Sign up at SerpApi to get an API key if you want the assistant to be able to search Google for you.

### 5. YouTube API
Enable the YouTube Data API v3 in your Google Cloud project to allow the assistant to find tutorials and videos.

## Requirements
- A running instance of n8n
- A WhatsApp Business account
- API keys for the services mentioned above

## License
This project is shared under the Apache License 2.0.

