---
description: Search past decisions across accepted, rejected, and graveyard files. Use when you need to find a specific flaw or decision from a previous session.
---

# Search Decisions

The user wants to search past decisions. The search term is: "$ARGUMENTS"

1. Determine which file is most likely to contain what the user is looking for based on their query.
2. Search that file first. If found, present the results.
3. If not found, search the remaining files.
4. Search order priority:
   - If the query implies something they acted on → `RM_accepted.md` first
   - If the query implies something they dismissed → `RM_rejected.md` first
   - If the query implies something old or buried → `RM_graveyard.md` first
   - If unclear → search in order: `RM_accepted.md` → `RM_rejected.md` → `RM_graveyard.md`
5. Present matching entries with their current location (which file they're in).
6. If entries are found in the graveyard, ask: "This was graveyarded. Want to reincorporate it?"
