# Co-development protocol (Grok / ChatGPT / Gemini)

Private repo `lattice` is the operating copy. Public repo `lattice-audit` is what unauthenticated models can read.

## Roles

- ChatGPT: mechanical auditor. GO/NO-GO only. No new thesis.
- Gemini: operator-psychology + kill-file observability.
- Grok: implementer of SPEC + software. Does not click the broker.

## Loop

1. Operator pastes AUDIT_PROMPT.md into ChatGPT and Gemini.
2. Only mechanical defects come back to Grok.
3. Grok patches SPEC or tests. No new names.
4. Operator funds the STAGED table when both say GO *and* MODE=STAGED is frozen.
5. Fills: `TICKER — dollars — price` into EXECUTION-LOG.

Stop after a GO. Another theory pass after GO is avoidance.
