# AI-Powered Lead Enrichment

## Problem
Sales teams spending hours manually writing personalized outreach emails for every new lead that comes in.

## Solution
This n8n workflow detects new leads in Google Sheets, uses Groq AI to generate a personalized outreach email, saves it back to the sheet, and notifies Slack.

## Tools
| Tool | Role |
|------|------|
| Google Sheets Trigger | Detects new leads |
| Edit Fields | Builds the AI prompt |
| HTTP Request | Calls Groq AI to generate email |
| Google Sheets | Saves generated email back to sheet |
| Slack | Notifies team of new lead + email |

## Outcome
✅ Personalized outreach email generated and saved within 60 seconds of a new lead. Sales team notified instantly on Slack.

## Setup
1. Import `workflow.json` into n8n
2. Connect Google Sheets, Slack and Gmail credentials
3. Replace Groq API key in the HTTP Request node
4. Add an "AI EMAIL" column to your Google Sheet
5. Publish the workflow

## Demo
🎥 [Watch demo](YOUR_LOOM_LINK_HERE)
