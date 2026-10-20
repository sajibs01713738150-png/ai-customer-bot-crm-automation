# AI-Powered Customer Support Agent & CRM Automated Booking Bot

An end-to-end autonomous B2C/B2B lead generation and customer onboarding system built using Voiceflow, Make.com, Calendly, and HubSpot CRM. 

## 🚀 Key Architectural Features
- **AI RAG Support Agent:** Handles customer queries 24/7 utilizing a dynamic Knowledge Base powered by LLM (GPT-4o mini) via Voiceflow's Agentic Core.
- **Autonomous Data Harvesting:** Captures user information (`Name` and `Email`) seamlessly during live conversation.
- **Real-Time CRM Synchronization:** Utilizes a secure webhook integration bridge built on Make.com to instantly push harvested leads directly into **HubSpot CRM**.
- **Dynamic Scheduling Pre-fill:** Automatically returns a custom, personalized **Calendly** scheduling URL with customer parameters pre-filled to maximize conversion rates.

## 🛠️ Technology Stack Used
- **Frontend / Conversational Layer:** Voiceflow (AI Agent Core)
- **Middleware / Integration Engine:** Make.com (Webhooks Architecture)
- **CRM Integration:** HubSpot CRM Dashboard
- **Scheduling Infrastructure:** Calendly API / Custom Tracking Parameter Injection .
