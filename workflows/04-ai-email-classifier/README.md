# AI Email Classifier & Auto-Responder

## Problem
Inboxes flooded with mixed emails — sales inquiries, support requests, spam — all requiring manual reading and replies.

## Solution
This n8n workflow watches a Gmail inbox, classifies each new email using Groq AI, and automatically sends a professional reply.

## Tools
| Tool | Role |
|------|------|
| Gmail Trigger | Watches inbox for new emails |
| Edit Fields | Builds the AI prompt |
| HTTP Request | Calls Groq AI to classify and draft reply |
| Gmail | Sends the auto-reply |

## Outcome
✅ Every new email classified and replied to automatically within 60 seconds.

## Setup
1. Import `workflow.json` into n8n
2. Connect Gmail and Groq credentials
3. Replace Groq API key in the HTTP Request node
4. Publish the workflow

## Demo
🎥 [Watch demo](YOUR_LOOM_LINK_HERE)
