# Google Sheets → Slack Notification

## Problem
Teams missing new leads or signups because there's no alert system when a new row is added to a spreadsheet.

## Solution
This n8n workflow watches a Google Sheet for new rows and instantly sends a formatted Slack notification.

## Tools
| Tool | Role |
|------|------|
| Google Sheets Trigger | Detects new rows |
| Slack | Sends notification |
| Gmail | Error alerts |

## Outcome
✅ Team notified in Slack within 60 seconds of every new submission. Zero missed leads.

## Setup
1. Import `workflow.json` into n8n
2. Connect Google Sheets, Slack and Gmail credentials
3. Set your target Sheet and Slack channel
4. Publish the workflow

## Demo
🎥 [Watch demo](YOUR_LOOM_LINK_HERE)
