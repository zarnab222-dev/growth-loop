# Growth Loop

A diagnostic-first system for improving at a skill through evidence instead of guesswork.

## Flow

1. **Diagnose** — classify current knowledge as Strong, Usable, Brittle, or Missing.
2. **Plan** — compress what is strong, drill what is usable, rebuild what is brittle, and sequence what is missing.
3. **Check in** — compare the plan against real evidence and update it when needed.

## Use

The portable version is in `PORTABLE-PROMPT.md`.

For environments that support reusable skills, use these in order:

```text
growth-intake
growth-plan
growth-checkin
```

State is stored under:

```text
growth/foundation-map.md
growth/plan.md
growth/log.md
```

## Contents

- `skills/growth-intake/` — adversarial diagnostic interview;
- `skills/growth-plan/` — evidence-based study plan;
- `skills/growth-checkin/` — periodic plan validation;
- `PORTABLE-PROMPT.md` — tool-agnostic prompt version.

## Limits

- A conversational diagnostic is a hypothesis about skill, not a substitute for performance evidence.
- Model agreeableness can soften judgments. Use artifacts, exercises, and real outcomes to correct the map.
- Re-run the full diagnostic when the goal changes or repeated evidence conflicts with the current map.
