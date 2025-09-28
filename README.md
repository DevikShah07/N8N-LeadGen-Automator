# LeadGen Automator 🚀

An **AI-powered lead generation and outreach automation system** built using [n8n](https://n8n.io/), APIs, and AI models. This project automates the process of scraping business leads, cleaning website content, generating summaries, creating personalized outreach emails, and storing results in Google Sheets.

---

## ✨ Features

* **Lead Collection**: Fetches business leads from Google Maps using Apify API.
* **Domain Validation**: Extracts and verifies website domains.
* **Web Scraping & Cleaning**: Retrieves website content and removes noise like scripts, styles, and ads.
* **AI Summarization**: Uses AI models to create concise business summaries.
* **Email Generation**: Generates professional, personalized HTML outreach emails.
* **Error Logging**: Captures and logs processing failures into a separate Google Sheet.
* **Dashboard Integration**: Updates a Google Sheet with leads, summaries, outreach status, and pipeline statistics.

---

## 🛠️ Tech Stack

* **Workflow Automation**: n8n
* **Data Sources**: Apify Google Maps Extractor
* **AI Models**: Hugging Face, OpenRouter/Groq APIs
* **Storage & Reporting**: Google Sheets
* **Scripting**: JavaScript (for custom nodes)

---

## 📂 Project Structure

```
.
├── E2M_Sol_Lead_Gen_Project.json   # n8n workflow export (cleaned version)
├── README.md                       # Project documentation
└── /docs                           # (Optional) Screenshots or workflow diagrams
```

---

## 🚀 How It Works

1. **Fetch Initial Leads** → Apify scrapes businesses from Google Maps.
2. **Process Leads** → Extracts details like name, website, phone, address, etc.
3. **Domain Validation** → Checks if the business has a valid domain.
4. **Web Scraping** → Collects content from the company’s website.
5. **Content Cleaning** → Removes unnecessary HTML, extracts key text.
6. **AI Summarization** → Summarizes business info in 2–3 sentences.
7. **Outreach Email Generation** → AI generates personalized HTML emails.
8. **Google Sheets Integration** → Stores leads, summaries, emails, and stats.
9. **Error Logging** → Failed cases logged separately for review.

---

## 📊 Example Use Cases

* Automated **B2B lead generation** for marketing agencies.
* **Sales prospecting** with AI-personalized outreach.
* **Data enrichment** for CRM systems.

---

## 🔒 Security Note

The provided workflow has **all API keys and secrets removed**.
👉 Remember to add your own API credentials in n8n before running.

---

## ⚡ Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/leadgen-automator.git
   ```
2. Import the workflow into your **n8n instance**.
3. Add your credentials (Apify, Hugging Face, Google Sheets, etc.).
4. Run the workflow and watch the automation in action!

---

## 📌 Future Improvements

* Add **CRM integration** (HubSpot, Salesforce).
* Integrate with **email delivery services** (SendGrid, Mailgun).
* Build a **dashboard UI** for monitoring leads in real-time.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---
