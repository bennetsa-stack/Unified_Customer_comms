# 🛠️ TradeStream AI: Proof of Concept (Nashville)
An automated AI Dispatcher designed to bridge the gap between social media leads and trade business operations.

## 🚀 Current Project Status: Phase 3 (Sandbox Complete)
We have successfully built a "Cradle-to-Grave" automation loop that identifies service leads and schedules them without human intervention.

### 🧠 Features Implemented
* **AI Router Agent:** Deployed a logic-gate using Google Gemini to distinguish between general FAQs (pricing, service area) and actionable service leads.
* **Social Connectivity:** Established a secure Webhook bridge to a Facebook Business Sandbox via a permanent Page Access Token.
* **Persona Lock:** Configured a strict "Employee Persona" to ensure professional, Nashville-local customer interactions while suppressing developer-facing internal logic.
* **Lead Extraction:** Automated the collection of physical addresses and service types from unstructured chat data.
* **Calendar Synchronization:** Integrated a Google Calendar sink that converts identified leads into scheduled site-visit events automatically.

### 🛠️ The Tech Stack
* **Infrastructure:** Meta Developer Portal (Messenger API)
* **Orchestration:** Make.com (formerly Integromat)
* **AI Engine:** Google Gemini (Generative AI)
* **Database/Scheduling:** Google Calendar API
* **Debugging:** Meta Graph API Explorer

### 📈 Future Roadmap
* **Phase 4 (Scaling):** Transition from Sandbox to Verified Business Portfolio.
* **Phase 5 (Multi-Channel):** Deployment to Instagram DMs and WhatsApp Business API.
* **Phase 6 (Media Handling):** Automated storage of customer-sent photos into a localized Google Drive folder for quote preparation.
