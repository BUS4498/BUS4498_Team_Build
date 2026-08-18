---
name: replace-with-kebab-case-skill-name
description: >
  Use this Skill when [state the triggering situation and task]. Do not use it
  when [state the closest out-of-scope or near-miss situation].
---

# [Skill Title]

<!--
Complete this initial design after finishing Milestone 1 Sections 3.1-3.3.
Use only the assigned scenario and policy at this stage. Data, tools, and
controlled testing will be introduced in later milestones.
Delete every HTML comment before submitting the Skill.
Never include credentials, access tokens, personal information, confidential
data, or real customer data.
-->

## Purpose and Scope

This Skill helps the user [perform one specific task] when [triggering situation].

### In Scope

- [Request or responsibility the Skill should handle]
- [Request or responsibility the Skill should handle]

### Out of Scope

- [Closely related request the Skill should not handle]
- [Situation that should use a different Skill, workflow, or human decision]

## Required Inputs

<!-- State the minimum information the Skill needs before starting. -->

- [Required input and expected format]
- [Required input and expected format]

If a required input is missing, [state whether to ask a question, stop, or
escalate].

## Procedure

<!--
Write one default procedure. Use direct action verbs. Include decision points,
exception behavior, and stop conditions. Do not provide an unexplained menu of
approaches.
-->

1. [First action]
2. [Second action]
3. [Decision or validation step]
4. [Exception, escalation, or refusal step]
5. [Final quality check]

## Required Context

<!--
Keep short, frequently used context here. Link longer or reusable material from
references/ using a direct, one-level link.
-->

- [Policy, definition, rule, example, or data field needed]
- [Policy, definition, rule, example, or data field needed]

Supporting reference, if needed: [Reference name](references/file-name.md)

## Output Format

<!-- Provide the exact structure the Skill should return. -->

```text
[Required heading or field]
[Required heading or field]
[Decision, evidence, exception, or next-action field]
```

Supporting output asset, if needed: [Asset name](assets/file-name.md)

## Gotchas

<!--
Record important non-obvious rules, exceptions, conflicts, or assumptions that
are grounded in the assigned scenario or policy. If the materials do not
resolve an issue, label it as an open question rather than inventing a rule.
-->

- **[Non-obvious issue]:** [What to do and the scenario or policy basis]
- **[Non-obvious issue]:** [What to do and the scenario or policy basis]

## Supporting Files

<!--
List only files the Skill actually needs. If none are needed, keep the explicit
statement below and delete the example links.
-->

No supporting files are required because [brief explanation].

- [Reference file](references/file-name.md)
- [Output asset](assets/file-name.md)
- [Script](scripts/file-name.py)

## Final Self-Check

<!-- Delete this section before submitting the Skill. -->

- [ ] The name uses lowercase kebab-case.
- [ ] The description states when the Skill should and should not activate.
- [ ] The Skill has one task-scoped responsibility.
- [ ] The procedure provides one clear default method.
- [ ] Required inputs, stop conditions, and exception behavior are explicit.
- [ ] The output format is usable without additional explanation.
- [ ] Gotchas or exception rules are grounded in the scenario or policy and do not invent missing rules.
- [ ] Every supporting-file link opens and is only one level deep.
- [ ] Unused example links and placeholder text have been removed.
- [ ] No credentials, personal information, or confidential data are present.

