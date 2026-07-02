---
"mattpocock-skills": minor
---

Make the **`grilling`** interview show its work on every question. Instead of just offering a recommended answer, each question now lays out the realistic options with their trade-offs — a compact pros/cons table when there are two or more — then names the agent's recommendation _and the reasoning_ behind it (which trade-off it's weighting highest, and what would change its mind). When it can't recommend one without knowing more, it says what's missing rather than guessing.

Because `grilling` is the shared primitive, this flows through to both its user-invoked front doors, **`grill-me`** and **`grill-with-docs`**, and to every skill that leans on it (`improve-codebase-architecture`, `triage`). Docs pages for `grilling`, `grill-me`, and `grill-with-docs` are re-synced to describe the richer per-question format.
