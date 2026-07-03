# NEXUS Lead Qualification System

13-node n8n workflow that collects incoming leads, applies business rule scoring via Function nodes, stores qualified leads in Google Sheets, and sends instant Gmail alerts to the sales team.

## Tech
n8n (self-hosted) | Google Sheets API | Gmail | Function Node | Switch Node

## How to Use
1. Import the JSON file into n8n
2. Connect your Google Sheets and Gmail credentials
3. Customize lead scoring rules in the Function node
4. Activate the workflow
