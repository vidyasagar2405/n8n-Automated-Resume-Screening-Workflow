# n8n-Automated-Resume-Screening-Workflow

# 🚀 Resume ATS Checker Workflow (n8n)

An automated **Resume Screening System** built using **n8n**, Telegram, Google Sheets, and AI. It processes **PDF** or **ZIP (multiple PDFs)**, scores resumes using AI, updates sheets, and sends results automatically.

<img width="1470" height="956" alt="Resume ATS checker Snapshot" src="https://github.com/user-attachments/assets/5606418f-e885-4a0e-ba10-9f98fab114ce" />


## demo video :
[Youtube](https://youtu.be/a8wwLBGe3RU)
---

## 🔥 Key Features

* Upload resumes via **Telegram** (PDF or ZIP).
* **AI-powered ATS scoring**.
* Auto-classifies: **Accepted (≥70)** / **Rejected (<70)**.
* Append results to **Google Sheets**.
* Auto-send **Accepted/Rejected** messages.
* Supports **multiple resumes inside ZIP**.

---

## 📌 Workflow Steps

1. Telegram trigger receives file.
2. Switch: PDF → single flow, ZIP → loop flow.
3. Extract text → AI Analysis → Score.
4. Append to Accepted/Rejected Sheets.
5. Send message to user automatically.

---

## 🛠️ Tech Used

* n8n
* Telegram Bot API
* Google Sheets API
* AI (Gemini/LLM)

---

## ▶️ Usage

* Import workflow JSON into n8n.
* Add Telegram + Google Sheets credentials.
* Send PDF/ZIP to your bot and watch automation run.

