# Key Decisions & Tradeoffs

## Decisions I Would Not Make
- I would not customize core logic for individual customers at the expense of maintainability.
- I would not hide errors to preserve appearances; transparency reduces long-term risk.
- I would not bypass validation or security checks to gain short-term speed.

## When to Push Back
- When customer requests introduce hidden operational risk
- When proposed solutions violate platform constraints
- When custom behavior cannot be supported at scale

## When to Escalate
- Ambiguous product requirements
- Repeated edge-case failures
- Requests that imply roadmap-level changes
