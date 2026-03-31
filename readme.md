# 🚀 Job Application Tracker Bot (UiPath)

## 📌 Overview

The **Job Application Tracker Bot** is an automation solution built using UiPath that streamlines the process of tracking job-related emails from Gmail and organizing them into a structured Excel-based tracking system.

Instead of manually scanning inboxes and updating spreadsheets, this bot automatically extracts, classifies, and records relevant job application details — reducing effort, errors, and missed opportunities.

---

## ⚙️ Key Features

* 📥 **Automated Email Retrieval**
  Fetches emails directly from Gmail using UiPath GSuite activities.

* 🎯 **Smart Filtering Logic**
  Identifies job-related emails using keyword-based classification (e.g., job, hiring, interview, role, opening).

* 🧾 **Structured Data Extraction**
  Extracts and organizes:

  * Date received
  * Company / Sender
  * Job Title (Email Subject)
  * Application Status *(Interview / Test / Applied)*
  * Follow-up Date

* 📊 **Excel-Based Tracking System**
  Automatically logs all processed data into a structured Excel sheet.

* 🔁 **Duplicate Prevention**
  Ensures the same email is not recorded multiple times across runs.

* 🪵 **Execution Logging & Error Handling**
  Provides runtime logs and exception handling for better reliability and debugging.

---

## 🔄 Workflow

1. Connect to Gmail and retrieve emails from Inbox
2. Apply keyword-based filtering to identify job-related emails
3. Iterate through filtered emails
4. Extract relevant fields (date, sender, subject, status, etc.)
5. Check for duplicates
6. Store structured data into Excel

---

## 📁 Output

An Excel file (`Job_Tracker.xlsx`) containing structured job application records:

| Date | Company | Job Title | Status | Follow-up Date | Email Subject |
| ---- | ------- | --------- | ------ | -------------- | ------------- |

---

## 🛠️ Tech Stack

* **UiPath Studio**
* **UiPath GSuite Activities (Gmail Integration)**
* **Excel Automation**
* **VB.NET (UiPath Expressions)**

---

## 💡 Use Case

This bot is ideal for:

* Job seekers managing multiple applications
* Students applying to internships or placements
* Professionals tracking hiring processes

---

## 🚧 Future Enhancements

* 🧠 NLP-based email classification (replace keyword filtering)
* 📌 Advanced duplicate detection across historical data
* 📊 Dashboard integration for analytics & insights
* ⏰ Automated follow-up reminders
* ☁️ Cloud storage integration (Google Sheets / DB)

---

## ⚠️ Note

Authentication for Gmail is handled securely via UiPath.

---

## 🧑‍💻 Author

**Earnest S**

---