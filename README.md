# QA Session Checker — n8n Workflow

Automated Q&A checker that evaluates answers using AI and logs results to Google Sheets.

## Features
- Collects name, email, question, and answer via form
- Checks whether the email is a Gmail account
- Uses Google Gemini AI to evaluate answers
- Returns Correct/Incorrect with the correct answer if needed
- Stores all results in Google Sheets

## Tech Stack
- n8n
- Google Gemini API
- Google Sheets

## Setup
1. Import `practice_01.json` into n8n
2. Add your Google Gemini API credential
3. Connect your Google Sheets account
4. Activate the workflow
5. Share the generated form webhook URL
