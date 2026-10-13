# PMBot_user_instructions
User Instructions to prepare and use PMBot for Jira

PMBot: Jira to Telegram Integration

PMBot bridges Jira and Telegram to reduce administrative friction in Agile and Kanban teams. By integrating directly with Telegram, team members can report progress, flag blockers, and transition issues seamlessly, while project leaders receive automated daily digests.

This document outlines the required steps to configure PMBot for a new project and onboard team members.

1. Project Administrator Setup

Before team members can receive notifications, the project administrator must configure the core settings within the Jira workspace.

Access the Admin Panel: Navigate to your Jira project and open the PMBot Admin Panel from the sidebar.

Assign the Project Leader: Specify the primary project leader. This user will automatically receive the daily executive digests detailing the latest project updates, bottlenecks, and team activities.

Define Workflow Phases: Input the exact order of your project phases (e.g., Backlog, In Progress, In Review, Done). Establishing this sequence is mandatory, as it instructs PMBot on how to present transition options to users within Telegram.

2. Team Member Onboarding (Admin Actions)

To ensure secure routing, each team member must link their Jira account to their Telegram application using a unique integration link.

Generate Links: Within the PMBot Admin Panel, generate the unique Telegram integration links for the users you wish to onboard.

Create Onboarding Tasks: Go to your Jira project backlog and create a new task or issue for each team member.

Add the Integration Link: Paste the user's unique integration link directly into the description field of their respective task.

Assign the Task: Assign the task to the user. This serves as their official onboarding ticket.

3. Account Linking (End User Actions)

Team members must execute the following steps to finalize the integration.

Review the Task: The user opens the onboarding task assigned to them in the Jira backlog.

Execute the Link: The user clicks the integration link provided in the task description.

Authorize Telegram: The link will redirect the user to the Telegram application and initialize the bot. This action permanently binds their Jira account to their Telegram chat.

Data Security and Privacy Statement

PMBot is designed with data minimization as a priority. To route notifications between platforms, PMBot exclusively collects and stores the Atlassian accountId and maps it to a standard Telegram Chat ID.

PMBot does not collect, process, or store personal identifiable information (PII) such as usernames, email addresses, physical locations, or organizational job titles. All routing operations are processed securely via Google Cloud Platform infrastructure.
