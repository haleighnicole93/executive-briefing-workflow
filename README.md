# Executive Morning Brief Workflow

A real-world example of how I used Microsoft Copilot to reduce manual executive-prep work and create a consistent morning briefing workflow.

## The Problem

Preparing for a daily executive check-in meant reviewing multiple sources of information before the workday started:

- Recent email activity
- Flagged and pinned messages
- Teams messages
- The CEO's calendar
- Tasks and deadlines buried inside emails and meeting invitations

Doing this manually every morning was repetitive and made it easy to spend time searching for information instead of preparing for the decisions and priorities that actually mattered.

## What I Built

I created and refined a Microsoft Copilot prompt that reviewed the CEO's recent communications and calendar activity and produced a structured morning brief.

The prompt instructed Copilot to review:

- Read and unread emails from the previous 48 hours
- Flagged and pinned emails
- Relevant Teams messages from the previous 48 hours
- The CEO's calendar for the current day

The resulting brief included:

### Emails Requiring Attention
- Sender
- Subject
- Whether a response appeared to be needed
- A short draft response for urgent items when a response had not already been sent

### Today's Schedule
- Meetings and calls
- Start times
- Relevant calendar context

### Tasks & Deadlines
- Tasks mentioned in recent emails
- Deadlines mentioned in emails or calendar invitations
- Follow-up items that could affect the day ahead

## Output Format

I asked Copilot to organize the briefing into clear sections and bulleted lists so I could scan it quickly before my morning meeting with the CEO.

The goal was not to create a long summary. It was to surface the information most likely to require attention that day.

## Automation

After refining the prompt and output format, I scheduled the workflow to run every morning before the workday began.

This gave me a consistent briefing before my daily executive meeting without requiring me to manually rebuild the same review process every morning.

## Where AI Helped

Copilot handled the repetitive work of:

- Reviewing recent communication
- Summarizing relevant information
- Identifying possible follow-up items
- Drafting short responses
- Organizing information into a consistent briefing format

The final output still required human judgment to determine priority, sensitivity, accuracy, and what should actually be escalated to the executive.

## Why I Built It

The goal was simple: spend less time gathering information and more time walking into the morning executive meeting already prepared.

Rather than repeatedly searching through email, Teams, and the calendar, I could start the day with a structured view of the items most likely to matter.

## Confidentiality

This repository documents the workflow and methodology only.

Any examples included here are fictional or recreated for portfolio purposes. No confidential employer, executive, employee, financial, board, client, email, Teams, or calendar information is included.

## Project Files

- [Sample Input](sample-input.md) — fictional email, Teams, and calendar information used to demonstrate the workflow
- [Sample Executive Morning Brief](sample-brief.md) — example of the structured briefing output
- [Workflow Documentation](workflow.md) — step-by-step explanation of how the Copilot workflow was designed and scheduled
