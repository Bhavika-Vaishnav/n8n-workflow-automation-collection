# n8n Workflow Automation Collection

## Overview

This repository showcases four personal workflow automation projects developed using **n8n**. These workflows automate repetitive tasks, streamline project management activities, and improve communication through integrations with Google Sheets, webhooks, and email.

## Project Highlights

### 1. Auto-Close Inactive Tasks
- Automatically checks task records using a scheduled trigger.
- Retrieves task information from Google Sheets.
- Evaluates task conditions using IF logic.
- Updates task records based on the defined conditions.

### 2. Update Project Progress Charts
- Retrieves project information from Google Sheets.
- Processes project progress information.
- Updates spreadsheet records to maintain progress data.

### 3. Auto-Create Milestones and Subtasks
- Monitors project information through Google Sheets.
- Uses JavaScript logic to process milestone and subtask details.
- Automatically creates corresponding records in the spreadsheet.

### 4. PR Merge Notification Workflow
- Receives pull request events through a webhook.
- Checks event conditions.
- Sends email notifications when the configured merge condition is satisfied.

## Technology Stack

- **Workflow Automation:** n8n
- **Programming:** JavaScript
- **Data Management:** Google Sheets
- **Integration:** REST APIs, Webhooks
- **Notifications:** Email

## Repository Structure

```text
n8n-workflow-automation-collection/
│
├── README.md
├── demo/
│   ├── task-1-auto-close-inactive-tasks.mp4
│   ├── task-2-update-project-progress-charts.mp4
│   ├── task-3-auto-create-milestones-subtasks.mp4
│   └── task-4-pr-merge-notification.mp4
│
└── screenshots/
    ├── task-1/
    ├── task-2/
    ├── task-3/
    └── task-4/
```

## Key Learnings

- Designing automated workflows using n8n.
- Integrating Google Sheets with workflow automation.
- Implementing conditional logic and JavaScript processing.
- Working with webhooks and event-driven automation.
- Automating notifications and repetitive operations.

## Project Type

Personal Projects

## Author

**Bhavika Vaishnav**
