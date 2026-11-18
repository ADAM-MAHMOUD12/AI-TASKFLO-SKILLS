---
name: debug
description: Diagnose a software problem from evidence and verify the smallest safe fix.
---

# Debugging

Diagnose before changing code. Establish the exact symptom, expected behavior,
reproduction steps, and affected environment.

- Follow the failing path through the relevant code and inspect the actual
  error or test output.
- Identify the root cause and distinguish it from secondary symptoms.
- Make the smallest complete fix that preserves unrelated behavior.
- Add or update a focused regression test when practical.
- Run the narrowest relevant validation and report its result accurately.

Do not claim a fix is verified unless the relevant check has been run. If
evidence is incomplete, state the remaining uncertainty.
