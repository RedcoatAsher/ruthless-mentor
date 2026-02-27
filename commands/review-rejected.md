---
description: Review and manage your rejected flaws. Reincorporate them as accepted concerns or send them to the graveyard permanently.
---

# Review Rejected Decisions

The user wants to review their rejected flaws. Do the following:

1. Read `ruthless-mentor-log/RM_rejected.md` from the project root.
2. If the file doesn't exist or has no entries, tell the user: "No rejected flaws on the books. Either you've been accepting everything or I haven't been pushing hard enough."
3. If there are entries, present each one with its ID, title, summary, and context.
4. For each entry, ask the user to choose:
   - **Reincorporate** — move to `ruthless-mentor-log/RM_accepted.md` (remove from `ruthless-mentor-log/RM_rejected.md`)
   - **Graveyard** — move to `ruthless-mentor-log/RM_graveyard.md` (remove from `ruthless-mentor-log/RM_rejected.md`)
   - **Keep rejected** — leave in `ruthless-mentor-log/RM_rejected.md` for now
5. Execute their decisions. Remember: each entry lives in exactly one file. Remove from source, append to destination.
6. Summarize what changed.
