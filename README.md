# Reflection Sentiment Analyzer

## 🧠 What is it?

**Reflection Sentiment Analyzer** is a Google Sheets add-on designed for educators and advisors. It helps evaluate written student reflections by analyzing emotional tone, sentiment, and potential concern flags using Google’s Natural Language Processing (NLP) tools.

---

## ✨ Features

- ✅ Automatically detects **positive**, **negative**, and **neutral** sentiment
- 💬 Tags emotional keywords with visual emoji indicators
- 🚨 Flags high-priority concern words (e.g., related to well-being or distress)
- ⚠️ Identifies reflections that may be **too short** to evaluate meaningfully
- 🔄 Can be scheduled to **update automatically** or run manually
- 🔎 Designed to be transparent, interpretable, and educator-friendly

---

## 🔐 Privacy Policy

### What data does the add-on access?
- Only the **reflection columns you manually select** within your Google Sheet.
- No personal information (names, emails, IDs) is accessed or stored.
- All sentiment analysis is processed via **Google’s Cloud Natural Language API**.

### What is stored?
- **Nothing** is stored outside of your spreadsheet.
- No data is sent to third-party servers — all processing happens within Google services.

### Third-party services
This add-on uses:
- [Google Cloud Natural Language API](https://cloud.google.com/natural-language)  
  for secure and private sentiment analysis

### Permissions used
This add-on requests the following permissions:
- `spreadsheets` – to read/write selected reflections and results
- `script.container.ui` – to display the column selection sidebar
- `script.external_request` – to send text to Google's NLP API

---

## 👩‍🏫 Who is this for?

Reflection Sentiment Analyzer was built for:
- Tutoring centers
- Academic advisors
- Instructors using reflective assignments
- Educational researchers

It is especially useful for reviewing large volumes of reflections efficiently, while maintaining student well-being as a priority.

---

## 🧩 About the Developer

This project was created as part of a graduate internship in Human Language Technology at the University of Arizona.  
For questions, feedback, or feature requests, please contact: **leliarhodes72@gmail.com**

---



