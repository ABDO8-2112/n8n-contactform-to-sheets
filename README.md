# 📬 Contact Form to Google Sheets Automation (n8n Workflow)

This project is a no-code automation built using [n8n](https://n8n.io) that receives data from a contact form via Webhook and appends it to a Google Sheet in real time.

It’s designed as a plug-and-play workflow that can be used for:

- Website contact forms
- Lead capture forms
- Internal submission tools
- CRM input

---

## ⚙️ How It Works

1. A contact form (or API request) sends data via HTTP POST to the n8n Webhook URL.
2. The workflow receives the JSON payload using a **Webhook node**.
3. The data is mapped and passed to a **Google Sheets node**.
4. A new row is appended in your Google Sheet instantly.

---

## 🔧 Tools & Services Used

- **n8n** – Open-source workflow automation
- **Google Sheets API** – Appends data to spreadsheet
- **Docker** – Self-hosted local environment
- **Webhook** – Captures incoming data
- **OAuth2** – Secure Google account integration

---

## 📂 Files Included

| File                     | Description                                      |
|--------------------------|--------------------------------------------------|
| `workflow.json`          | Exported n8n workflow (import to replicate)      |
| `sample-request.json`    | Example POST payload for testing                 |
| `screenshots/`           | Workflow
