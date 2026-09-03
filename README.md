# n8n AI Voice Assistant Templates

A collection of [n8n](https://n8n.io/) workflow templates designed to power intelligent AI voice assistants. These workflows handle everything from initial voice gateway routing to advanced RAG (Retrieval-Augmented Generation) and automated appointment booking.

## 🚀 Workflows Included

- **Core Voice Gateway:** The central routing hub that receives incoming voice requests and orchestrates the logic between different sub-workflows.
- **Knowledge Base RAG Workflow:** Integrates with vector databases to perform Retrieval-Augmented Generation, allowing the voice assistant to answer questions based on custom knowledge bases.
- **Web Scraper & Knowledge Base Updater:** An automated pipeline that scrapes specified websites and dynamically updates the vector database to keep the voice assistant's knowledge fresh.
- **Appointment Booking Workflow:** Handles calendar integrations to check availability and book appointments dynamically during voice calls.
- **Call Analytics & Logging:** Automatically logs call transcripts, metadata, and outcomes for analytics and quality assurance.

## 🛠️ Usage
1. Import the `.json` files directly into your n8n instance.
2. Update the credential nodes (e.g., OpenAI, Vector DB, Calendar API) to match your environment.
3. Connect the Webhook URLs to your preferred Voice AI provider (e.g., Vapi, Twilio).

*Feel free to use and adapt these templates for your own voice automation projects!*
