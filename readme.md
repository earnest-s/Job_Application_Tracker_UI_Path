# Job Application Tracker Bot (UiPath)

## Overview
This project automates tracking of job-related emails from Gmail and logs them into an Excel sheet.

## Features
- Fetch emails from Gmail using UiPath GSuite activities
- Filter job-related emails using keyword-based logic
- Extract structured information:
  - Date
  - Company (Sender)
  - Job Title (Subject)
  - Status (Interview / Test / Applied)
  - Follow-up Date
- Automatically store data into Excel

## Workflow
1. Retrieve emails from Inbox
2. Apply keyword filtering (job, hiring, interview, etc.)
3. Loop through filtered emails
4. Extract required fields
5. Store results in Excel

## Output
Excel sheet with structured job tracking data

## Tech Stack
- UiPath Studio
- Gmail API (GSuite Activities)
- Excel Automation

## Future Improvements
- NLP-based email classification (replace keyword filtering)
- Duplicate detection
- Dashboard integration
- Auto follow-up reminders