# Weekly Report → Gmail Digest

## Problem
Business owners and managers spending hours every Monday manually pulling data from spreadsheets and writing weekly summary reports.

## Solution
This n8n workflow runs automatically every Monday at 8am, pulls all data from Google Sheets, uses Groq AI to generate a professional summary report, and emails it directly to your inbox.

## Tools
| Tool | Role |
|------|------|
| Schedule Trigger | Fires every Monday at 8am |
| Google Sheets | Pulls all submission data |
| Edit Fields | Formats data into a readable prompt |
| Aggregate | Combines all rows into a sin
