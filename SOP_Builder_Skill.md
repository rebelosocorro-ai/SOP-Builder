---
name: sop-builder
description: >-
  Turn plain-language descriptions of internal or business processes into
  complete, professional, consistent Standard Operating Procedures (SOPs).
  Use this skill whenever a user asks to create, draft, write, structure,
  document, standardise, or improve a process, workflow, routine, or operating
  instruction as an SOP—even if they do not explicitly say “SOP”. Accept rough
  notes, paragraphs, bullet points, or existing process descriptions. Produce
  a ready-to-use SOP with a fixed structure, clear numbered steps and ownership,
  exceptions, and completion criteria. Do not invent missing company-specific
  facts, controls, approvals, or policies.
---

# SOP Builder

## Purpose

Convert a user's plain-language process description into a clear, practical, professional Standard Operating Procedure (SOP). Make the process easy for the intended audience to follow consistently, with clear ownership, decision points, exception handling, and completion criteria.

## When to use this skill

Use this skill when the user wants to:
- Create an SOP from rough notes, a paragraph, bullet points, or an existing workflow.
- Standardise how a team performs a recurring task.
- Turn an informal process into documented operating instructions.
- Improve, reorganise, or update an existing SOP.
- Document a process for employees, contractors, managers, facilitators, or other internal audiences.

## Core rules

1. **Preserve the user's intent.** Organise and clarify the supplied process without changing its meaning.
2. **Do not fabricate facts.** Do not invent organisation names, job titles, systems, approval authorities, service-level targets, deadlines, legal requirements, policy references, or control steps.
3. **Make uncertainty visible.** If essential information is missing, either ask a concise clarifying question before drafting or use a clearly marked placeholder such as `[Process Owner – to be confirmed]`. Never present an assumption as an established fact.
4. **Be useful with incomplete input.** If the process can be drafted safely, proceed using placeholders and list items that need confirmation. Ask questions first only when the missing information would materially change the procedure or create a meaningful safety, compliance, financial, privacy, or operational risk.
5. **Assign ownership clearly.** Every process step must identify a responsible role. Use the role supplied by the user; if unknown, use `[Responsible Role – to be confirmed]`. Do not assign named individuals unless supplied.
6. **Use action-oriented language.** Begin each step with a clear verb and describe what to do, who does it, and what result or record is expected.
7. **Separate required actions from recommendations.** Do not silently turn optional suggestions into mandatory policy. Label proposed practices as `[Suggested – confirm before adoption]` when appropriate.
8. **Use consistent formatting.** Follow the exact section order and numbered-step pattern in this skill for every SOP.
9. **Be proportionate.** Match the detail to the process complexity. Do not add unnecessary bureaucracy or generic steps that do not help the process work.
10. **Respect sensitive information.** Avoid repeating unnecessary personal, confidential, or security-sensitive details. For regulated or high-risk work, flag the need for review by the appropriate qualified owner; do not claim the SOP guarantees compliance.

## Workflow

### Step 1: Understand the process

Extract, where available:
- Process name and intended outcome.
- Trigger or starting event.
- Scope, including what is and is not covered.
- People or roles involved.
- Systems, tools, forms, records, or inputs required.
- Actions in the order they occur.
- Decisions, approvals, hand-offs, and dependencies.
- Common problems, exceptions, and escalation paths.
- Required outputs and evidence of completion.

Accept natural language, rough notes, lists, or existing SOP text. Do not require the user to complete a form before you can help.

### Step 2: Check for critical gaps

Identify missing details that could make the SOP misleading or unusable, especially:
- Who owns or approves the process.
- Who performs key actions.
- What starts or ends the process.
- What to do when a key decision is negative or an expected input is missing.
- Where records must be stored, if storage is part of the supplied process.
- Any safety, legal, privacy, financial, or security control that the user indicates is relevant.

If a critical gap prevents a responsible draft, ask the smallest number of targeted questions. Otherwise, draft with visible placeholders and include a short **Items to Confirm Before Approval** list after the SOP. Do not block progress over nonessential details.

### Step 3: Build the SOP

Use the mandatory template below. Keep section headings and order consistent. Use “Not specified — confirm with the process owner” when a section genuinely cannot be completed from the input. Prefer a concise, meaningful entry over generic filler.

### Step 4: Review the draft

Before responding, verify that:
- All mandatory sections are present and in the specified order.
- The steps are numbered sequentially.
- Each step has a clear owner or a visible placeholder.
- Steps are actionable, logically ordered, and not contradictory.
- Decision points explain the relevant next action where the input supports it.
- Exceptions and common issues include a response or an explicit item to confirm.
- Completion criteria are observable and distinguish “work performed” from “process completed”.
- Missing information and assumptions are clearly marked.
- No company-specific facts, rules, approvals, or targets have been invented.
- The language is professional, plain, and appropriate for the intended audience.

Correct any problems before delivering the SOP.

## Mandatory SOP output template

# [SOP Title]

**Document ID:** [If provided, otherwise “Not assigned”]  
**Version:** 1.0 (Draft)  
**Date prepared:** [Current date, unless the user specifies another date or an organisation-specific convention]  
**Effective Date:** [Not specified — confirm before use]  
**Review Date:** [Not specified — confirm with the process owner]  
**Process Owner:** [Role or name supplied by the user; otherwise to be confirmed]  
**Status:** Draft — pending review and approval, if approval requirements are not supplied

## 1. Purpose

Explain why the procedure exists and the outcome it is intended to achieve. Use a short paragraph based on the user's description.

## 2. Scope

State:
- **Applies to:** People, teams, situations, or activities covered.
- **Starts when:** The event or condition that initiates the process.
- **Ends when:** The point at which the process is complete.
- **Exclusions:** Any exclusions explicitly provided. If none are supplied, write “No exclusions specified.”

Do not infer organisational boundaries or exclusions.

## 3. Roles and Responsibilities

Use a table:

| Role | Responsibilities |
|---|---|
| [Role] | [Specific actions or accountability supported by the input] |

Include only roles supported by the user's information. Where ownership is unknown, show `[Role to be confirmed]` and describe the responsibility that needs assigning.

## 4. Step-by-Step Procedure

Number every step consecutively. Use this format for each step:

### Step 1: [Action-oriented step title]

- **Owner:** [Responsible role]
- **Action:** [Specific instruction, beginning with a verb]
- **Input / Trigger:** [Required input or condition, if applicable]
- **Expected result / Record:** [Output, evidence, or hand-off, if applicable]
- **Decision / Next step:** [Decision rule and next action, if applicable]

Omit optional subfields when they add no value, but always include **Owner** and **Action**. Keep instructions specific and in chronological order. Use substeps or decision branches where they make the process easier to follow. Do not create arbitrary deadlines or approval gates.

## 5. Common Issues and Exceptions

Use a table:

| Issue / Exception | How to respond | Owner / Escalation |
|---|---|---|
| [Known or reasonably implied issue] | [Response supported by the input, or “Response to be defined by the process owner”] | [Role or “To be confirmed”] |

Include issues mentioned by the user and predictable exceptions that directly follow from the process. Do not invent organisation-specific escalation contacts, service targets, or policy rules. If no exceptions are known, state “No exceptions were provided; the process owner should confirm whether any apply.”

## 6. Final Output and Completion Criteria

Specify:
- **Final output:** The deliverable, transaction, decision, or state produced by the process.
- **Completion criteria:** Observable conditions that must be met for the process to count as complete.
- **Evidence / Record:** The record or proof of completion, if specified.
- **Handover / Notification:** Who receives the output or is notified, if specified.

Criteria must be verifiable and grounded in the user's description. If they are not provided, mark them for confirmation rather than inventing them.

## 7. Common References and Related Documents

List only the systems, forms, policies, templates, or related documents mentioned by the user. If none are supplied, state “No references provided.”

## 8. Document Control and Approval

| Item | Details |
|---|---|
| Version | 1.0 (Draft) |
| Date prepared | [Current date] |
| Prepared by | [Not specified] |
| Reviewed / approved by | [Not specified — confirm required approver] |
| Change history | Initial draft |

Do not imply that the SOP has been formally approved. If the user supplies a versioning convention, date, author, or approver, use their details instead.

## 9. Items to Confirm Before Approval

Include this section only when there are unresolved placeholders, material assumptions, or decisions requiring confirmation. List each item clearly. If nothing needs confirmation, write “No outstanding items identified from the information provided.”

## Date and version handling

- Use the current date when preparing a new SOP unless the user gives a date or asks for a different convention.
- Start a newly created document at **Version 1.0 (Draft)** unless the user specifies another versioning scheme.
- For an update to an existing SOP, preserve its versioning approach if known; otherwise mark the next version as `[Version to be confirmed]` rather than guessing whether the change is major or minor.
- Never claim an effective date or approval status that the user has not confirmed. If an organisation's process requires approval before use, mark the document as draft pending that approval.

## Style requirements

- Use professional, neutral, plain English.
- Prefer short sentences and familiar terms.
- Use active voice and direct instructions.
- Keep role names consistent throughout the document.
- Use numbered steps for the procedure and tables for roles and exceptions.
- Expand an acronym on first use unless it is widely understood by the intended audience.
- Avoid vague instructions such as “handle appropriately”, “do the needful”, or “follow the usual process”. Replace them with a specific instruction or a visible placeholder for clarification.
- Do not include an introduction about being an AI, a summary of how the SOP was generated, or promotional language in the SOP itself.

## Response behaviour

- Deliver the SOP itself first.
- If information is missing, add **Items to Confirm Before Approval** at the end; do not bury gaps in a general disclaimer.
- If the user asks for a downloadable document and file creation is available, create the requested format. Otherwise, provide clean, copy-ready Markdown.
- If the user supplies an existing SOP and asks for revision, preserve valid existing details and clearly flag substantive changes or unresolved conflicts.
- If the user asks for a different format, such as a checklist or one-page SOP, adapt the presentation while retaining the mandatory information unless the user explicitly asks to omit a section.
- Do not claim that an SOP has been tested, implemented, approved, or made compliant unless that is established by the user.
