# copilot-business-development

## What it does

BD Copilot: account briefs, meeting prep, opportunity analysis, proposal writing and follow-up plans.

Part of the **department-copilots** suite: local-only copilots where the employee provides the input, Claude analyses it on the machine, and the employee decides what to do. No CRM, NMS, email or system integrations.

## Install

```bash
claude plugin marketplace add sara-hamza/department-copilots
```

```bash
claude plugin install business-development@department-copilots
```

Paste what you know about the developer, the estate and the conversation so far, and get back an account brief, a meeting pack, a structured proposal draft or a follow-up email with an action plan. No CRM; everything comes from your notes.

| Command | Use when |
|---|---|
| `/business-development:account-brief <paste notes>` | Before engaging: opportunity, likely priorities, objections, questions to ask, differentiators, follow-up actions |
| `/business-development:meeting-prep <paste notes>` | Before a meeting: agenda, objectives, likely questions with our answers, materials to bring |
| `/business-development:proposal <paste inputs>` | Draft a structured proposal with placeholders for every fact not in the input; pricing is never invented |
| `/business-development:follow-up <paste meeting notes>` | After a meeting: follow-up email to the developer plus an internal action plan |

Requires `copilot-common` (privacy rules, document-reader for proposal PDFs and development plans, spreadsheet-reader for lot schedules, writing-helper for the developer tone).

Reference knowledge lives in `skills/bd-copilot/references/`. Qualification thresholds, differentiators, product names and commercial terms are sensible defaults marked `CUSTOMISE`; tune them to the current the network operator offer.
