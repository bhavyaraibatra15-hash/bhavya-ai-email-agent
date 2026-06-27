# bhavya-ai-email-agent
# 📧 AI Email Assistant with n8n

An intelligent AI-powered email assistant built using **n8n**, **OpenAI/Anthropic**, **Gmail API**, and **Google Sheets**. The workflow automatically analyzes incoming emails, classifies their intent, drafts professional responses, organizes the inbox, and logs all processed emails for tracking.

---

## 🚀 Features

* 📩 Automatically monitors new Gmail emails
* 🧠 AI-powered email understanding and classification
* ✍️ Generates professional draft replies
* 📌 Determines whether a reply is required
* 🏷️ Automatically adds Gmail labels
* 📊 Logs processed emails into Google Sheets
* 🚨 Detects high-priority emails and sends notifications
* 🔄 Prevents repetitive manual email processing
* ⚡ Built entirely using a low-code AI automation workflow

---

## 🏗 Workflow Overview

```text
Gmail Trigger
      │
      ▼
AI Agent
      │
      ▼
IF (Reply Needed?)
      │
 ┌────┴────┐
 │         │
No        Yes
 │          │
End   Create Gmail Draft
             │
             ▼
      Add Gmail Label
             │
             ▼
      Append to Google Sheets
             │
             ▼
      IF (Priority = High)
             │
      Send Notification
```

---

## 🛠 Tech Stack

* n8n
* OpenAI API / Anthropic API
* Gmail API
* Google Sheets API
* AI Agent
* Structured Output Parser
* Conditional Logic (IF Nodes)
* Workflow Automation

---

## 📂 Project Structure

```
.
├── workflow/
│   └── ai-email-assistant.json
├── screenshots/
├── docs/
├── README.md
└── LICENSE
```

---

## 📌 AI Capabilities

The AI agent automatically:

* Identifies the sender's intent
* Classifies email category
* Determines reply priority
* Generates professional draft replies
* Summarizes notifications and newsletters
* Detects emails that do not require a response

Supported categories include:

* Business Inquiry
* AI Project Inquiry
* Automation Consultation
* Internship
* Job Opportunity
* Support
* Partnership
* Investment
* Meeting Request
* Newsletter
* Notification
* Spam
* Personal

---

## 📈 Workflow Steps

1. Gmail Trigger detects a new email.
2. AI analyzes the email content.
3. AI returns structured JSON output.
4. Workflow checks whether a reply is required.
5. Draft reply is created in Gmail.
6. Gmail label is applied.
7. Email details are stored in Google Sheets.
8. High-priority emails trigger an additional notification.

---

## 📷 Screenshots

Add screenshots here after uploading them:

* Complete Workflow
* Gmail Draft
* Gmail Labels
* Google Sheets Log

---

## 🔒 Security

This repository does **not** include:

* API Keys
* Gmail Credentials
* OAuth Tokens
* Google Sheets Credentials
* Personal Email Data

---

## 🚀 Future Improvements

* Retrieval-Augmented Generation (RAG)
* CRM Integration
* Multi-Agent AI System
* Google Calendar Integration
* Human Approval Workflow
* WhatsApp Cloud Notifications
* Slack & Telegram Notifications
* AI Confidence Scoring
* Duplicate Email Detection

---

## 👨‍💻 Author

**Bhavya Rai Batra**

Founder, **Bhavya AI Labs**

---

## ⭐ If you found this project useful

Consider giving this repository a ⭐ on GitHub.
