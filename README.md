# YouTube-transcript

AI-powered YouTube transcript automation workflow using n8n, DeepSeek AI, Google Sheets, RapidAPI and automated SEO content generation.

---

# Overview

This project automates the process of transforming YouTube videos into SEO-ready content automatically.

The workflow:

- Detects YouTube links from Google Sheets
- Extracts YouTube transcripts
- Combines and cleans transcript data
- Generates SEO descriptions using AI
- Generates 10 viral YouTube titles
- Updates Google Sheets automatically
- Sends email notifications

---

# Workflow Architecture

```txt
Google Sheets
   ↓
Loop Over Items
   ↓
Extract Link
   ↓
Extract YouTube ID
   ↓
RapidAPI Transcript Extraction
   ↓
Transcript Parser
   ↓
Transcript Combiner
   ↓
AI Description Generator
   ↓
Description Cleaner
   ↓
AI Viral Title Generator
   ↓
Title Cleaner
   ↓
Google Sheets Update
   ↓
Gmail Notification
```

---

# Technologies Used

- n8n
- DeepSeek AI
- Google Sheets API
- Gmail API
- RapidAPI
- JavaScript

---

# Features

✅ Automatic transcript extraction  
✅ AI-generated SEO descriptions  
✅ AI-generated viral YouTube titles  
✅ Automated Google Sheets processing  
✅ Email notifications  
✅ Loop processing system  
✅ AI workflow automation  

---

# How It Works

The user simply pastes YouTube links inside Google Sheets.

The workflow automatically:

1. Detects the video
2. Extracts transcript
3. Generates optimized descriptions
4. Generates viral titles
5. Updates the sheet
6. Sends confirmation email

The workflow loops continuously through rows marked:

```txt
NEXT
```

Then updates them automatically to:

```txt
DONE
```

after processing.

---

# Google Sheets Structure

| Video Link | Statuts | Description | Title Ideas |
|---|---|---|---|

---

# Workflow Goal

The objective of this project is to create a semi-autonomous AI-powered YouTube content engine capable of transforming raw video content into optimized publishing assets automatically.

---

# Future Improvements

- Thumbnail AI generation
- YouTube auto-posting
- AI scoring system
- Multi-language support
- Telegram integration
- Notion integration
- Content farm architecture

---

# Important

Replace:

```txt
YOUR API KEY
```

with your own RapidAPI key before running the workflow.

---

# Author

Al Bin Zeti

---

# Status

Production Ready — V1 Stable
