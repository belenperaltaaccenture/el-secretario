# Proposed Automation: Friday Review

## Trigger

Every Friday at 5:00 PM, provided the tool and plan allow scheduled tasks on this folder.

## Context

- `INSTRUCTIONS_AI.md`
- `01_BUSINESS/BUSINESS_CONTEXT.md`
- new notes in `00_ENTERED`
- active projects in `06_PROJECTS`
- recent reviews in `07_REVIEWS`

## AI Work

Run the procedure in `prompts/WEEKLY_REVIEW.md`.

## Permitted Output

Prepare a draft review inside `07_REVIEWS` and notify that it is ready.

## Prohibited Actions

- publishing content;
- sending emails or messages;
- deleting or archiving sources;
- changing dates, owners, or priorities without evidence;
- modifying external services.

## Human Intervention Condition

The automation must stop and ask for a decision when it finds contradictory information, cannot identify a current source, or an action would have external consequences.
