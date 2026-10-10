# SOP Builder — Initial Test Review

## Scope

The skill was reviewed against three representative prompts: a routine internal process, a process with explicitly missing rules, and a process with an approval decision branch.

## Results

| Test | Required behaviour | Review |
|---|---|---|
| Employee onboarding | Required sections, clear HR/IT/manager ownership, placeholders for unknown details | Pass by design review |
| Customer complaint handling | No invented response deadlines or escalation rules; unknowns surfaced | Pass by design review |
| Shared-folder access | Approval branch explicit; no access without manager approval; no invented controls | Pass by design review |

## Checklist used

- Mandatory SOP sections appear in the prescribed order.
- Every procedure step has an owner and an action.
- Unknown roles, deadlines, approval details, and records are marked for confirmation.
- Decision branches preserve the user's stated rules.
- Completion criteria are observable and supported by the process description.
- Draft status is not confused with approval or implementation.
- No unsupported legal, security, or company-specific claims are added.

## Limitations

This is a structured manual review of the skill instructions against the test prompts, not an automated run inside Claude. The skill has not been executed in the user's Claude environment, and actual output quality should be checked after installation. The next practical validation is to paste each test prompt into Claude with the Skill enabled and compare the generated SOP against the checklist above.

## Recommended next step

Install or update the Claude Skill using `SKILL.md`, then run the three prompts in `evals/evals.json`. If any generated SOP invents a policy, omits a required section, or leaves a process step without an owner, revise the instructions and retest.
