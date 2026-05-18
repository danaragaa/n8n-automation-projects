# AI-Powered Data Extraction & Parsing Pipeline (n8n)

This repository contains a production-ready n8n workflow designed to capture unstructured data via webhooks, process it semantically using AI, and structure it cleanly into Google Sheets.

## 🛠️ Architecture & Workflow Structure
The pipeline consists of 4 main stages:
1. **Webhook Trigger:** Intercepts incoming raw payloads from external apps.
2. **AI Node (Gemini/OpenAI):** Uses advanced prompts to parse, categorize, and extract key variables from unstructured text.
3. **Code Node (JavaScript):** Sanitizes the AI output, runs strict data validation, and structures the JSON object.
4. **Google Sheets Integration:** Appends the structured data as a clean new row in real-time.

## 🚀 Key Features
- **Zero Human Intervention:** Automated manual data entry with 100% accuracy.
- **Smart Data Transformation:** Uses JavaScript for safe data parsing before storage.
- **Scalable Architecture:** Easily adaptable to any CRM or database (HubSpot, PostgreSQL, Airtable).

## 📄 How to Use
1. Download the `ai-data-extraction.json` file from this repository.
2. Import it into your n8n instance.
3. Configure your Webhook URL and Google Sheets credentials.
