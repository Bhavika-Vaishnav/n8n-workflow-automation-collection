# n8n Workflow Automation Collection

A collection of **four personal workflow automation projects** built using n8n, Google Sheets, JavaScript, webhooks, and Gmail.

These projects demonstrate how workflow automation can simplify repetitive tasks, manage project activities, and improve communication through automated processes.

## Projects Overview

### 1. Auto-Close Inactive Tasks

Automatically checks task records in Google Sheets and updates eligible tasks to Closed based on the configured conditions.

**Workflow:** Schedule Trigger → Google Sheets → IF → Update Row

[View Project 1](Project-1-Task-Auto-Close/README.md)

### 2. Update Project Progress Charts Automatically

Automates the retrieval and processing of project data in Google Sheets and updates the corresponding project progress information.

**Workflow:** Manual Trigger → Get Rows → Edit Fields → Update Row

[View Project 2](Project-2-Update-Project-Progress-Charts/README.md)

### 3. Auto-Create Milestones and Subtasks

Automatically creates milestone and subtask records in Google Sheets using a trigger and JavaScript processing.

**Workflow:** Google Sheets Trigger → Code in JavaScript → Append Row

[View Project 3](Project-3-Auto-Create-Milestones-Subtasks/README.md)

### 4. PR Merge Notification Workflow

Uses a webhook to receive Pull Request event data, evaluates the configured condition, and sends email notifications through Gmail.

**Workflow:** Webhook → IF → Gmail

[View Project 4](Project-4-PR-Merge-Notification/README.md)

## Technology Stack

- **Workflow Automation:** n8n
- **Data Management:** Google Sheets
- **Programming:** JavaScript
- **Event Handling:** Webhooks
- **Communication:** Gmail

## Repository Structure

```text
n8n-workflow-automation-collection/
│
├── Project-1-Task-Auto-Close/
│   ├── demo/
│   └── README.md
│
├── Project-2-Update-Project-Progress-Charts/
│   ├── demo/
│   └── README.md
│
├── Project-3-Auto-Create-Milestones-Subtasks/
│   ├── demo/
│   └── README.md
│
├── Project-4-PR-Merge-Notification/
│   ├── demo/
│   └── README.md
│
└── README.md
```

## Key Learnings

- Building multi-step workflows using n8n.
- Integrating Google Sheets with automation workflows.
- Using triggers and conditional logic.
- Processing data using JavaScript.
- Working with webhooks and event-based automation.
- Integrating Gmail for automated notifications.

## Project Information

- **Project Type:** Personal Projects
- **Total Workflows:** 4
- **Platform:** n8n

## Author

**Bhavika Vaishnav**
