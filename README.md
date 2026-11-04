# el-secretario

Initial structure designed to provide stable context to Codex, Claude, Gemini, or any other harness that can work with files.

The system is designed to:
- capture notes, meetings, and ideas without manually organizing them;
- preserve the original sources;
- separate decisions, tasks, questions, and content ideas;
- keep projects and products up to date;
- prepare a weekly review;
- automate drafts without publishing or sending anything on its own.

## Download or Clone

### Easy Option

1. Click the green **button**
2. Select **Download ZIP**
3. Extract the folder.
4. Open it using Codex, Claude Code, Gemini, or whichever tool you use.

### Using Git

```bash
git clone https://github.com/belenperaltaaccenture/el-secretario.git
```

## First Message for the AI

Copy the contents of [`MASTER_PROMPT_THE_SECRETARY.md`](MASTER_PROMPT_THE_SECRETARY.md) or tell it:

> Read README.md and INSTRUCTIONS_AI.md. Review the structure and explain how to use it. Do not modify any files yet.

Then complete [`01_BUSINESS/BUSINESS_CONTEXT.md`](01_BUSINESS/BUSINESS_CONTEXT.md) and add your first note inside `00_ENTERED`

## Structure

```text
00_ENTERED    Unprocessed notes
01_BUSINESS   Objectives and criteria: functional information
02_CLIENTS    Questions and real-world language
03_PRODUCTS   Dashboards, Apps, and Power Automate
04_CONTENTS   Ideas and drafts
05_PROCESS    Repeatable procedures
06_PROJECTS   Active work
07_REVIEWS    Weekly summaries
99_FILE       Inactive information
prompts          Reusable instructions
```

## Included Automation

[`prompts/WEEKLY_REVIEW_AUTOMATION.md`](prompts/WEEKLY_REVIEW_AUTOMATION.md) defines a Friday review. The AI can prepare the draft, but it must not publish, send messages, delete sources, or modify external services.

If your tool does not support scheduled tasks, manually run [`prompts/WEEKLY_REVIEW.md`](prompts/WEEKLY_REVIEW.md). The system will continue to work.

## Security and Privacy

This repository is public and contains only empty templates and reusable instructions.
When using it:
- do not upload real client information to a public repository;
- do not store passwords, API keys, card information, or personal documents;
- work locally or create a private repository for your real information;
- always review changes before publishing or sharing;
- keep a human in the loop for external actions.

## Main Rule
Files store the memory. AI processes it. Automations repeat it. The person decides.
