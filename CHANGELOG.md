# Changelog

## 1.0.0 — 2026-02-26

### Added
- Core ruthless mentor skill with 0-10 rating framework
- Proactive weakness hunting prioritized by relevance
- Four-file decision tracking: pending (buffer), accepted, rejected, graveyard
- Write-ahead buffer (`RM_pending.md`) for crash safety — flaws logged before user responds
- Session startup orphan check — clears pending items from interrupted sessions
- Zero-duplication architecture — each entry lives in exactly one file
- Unique entry IDs (RM-001, RM-002, etc.) that persist across file moves
- Token-efficient file access — only reads what's needed
- Periodic check-ins for rejected flaw review (randomized every 3-5 sessions)
- Graveyard retrieval on user-initiated search
- 12 swappable character personas (default + 11 characters) with persistent preference
- `/ruthless-mentor:persona` slash command for switching voices
- `/ruthless-mentor:review-rejected` slash command
- `/ruthless-mentor:search-decisions` slash command with smart file targeting
- Bulletproof loop — keeps pushing until it's ready to ship
