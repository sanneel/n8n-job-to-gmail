n8n Job Alerts Automation
Overview

This workflow automatically monitors remote job listings using the RemoteOK API, filters jobs based on selected keywords (Junior, Part-time, Developer, etc.), and sends email notifications when matching jobs are found.

The workflow runs on a schedule (every hour) and helps automate job discovery in real time.

Features

Scheduled execution (hourly job monitoring)

API integration (RemoteOK jobs API)

Keyword filtering using regex and conditions

Automated email notifications via Gmail

No manual job searching required

Workflow Architecture
Schedule Trigger
      ↓
HTTP Request (RemoteOK API)
      ↓
Filter (keywords: junior, part-time, developer, etc.)
      ↓
Gmail (Send notification email)

Nodes Used

Schedule Trigger – Executes workflow every hour

HTTP Request – Fetches jobs from https://remoteok.com/api

Filter – Filters jobs based on position/title/tags

Gmail – Sends email notification with job details

Email Output Example
New job found:

Location: Berlin
Company: Example Inc.
Link: https://remoteok.com/remote-jobs/example

Setup Instructions

Import workflow JSON into n8n

Connect your Gmail OAuth credentials

Adjust filtering keywords if needed

Activate the workflow

Use Case

This project demonstrates:

API data processing

Workflow automation

Conditional filtering logic

Real-time notification systems

Suitable for automation engineering, no-code/low-code workflow portfolios, and interview demonstrations.

Author

Sandro Siradze
