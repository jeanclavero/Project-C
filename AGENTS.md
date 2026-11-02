# Instructions for AI assistants

You are working with Jean on "Project C". Follow this file before anything else.

1. Read BUSINESS/status.md first — it tells you the current state and next steps.
2. Read BUSINESS/brief.md for what the project is, and BUSINESS/decisions.md
   for choices already made (do not re-litigate decided items unless Jean asks).
3. Read PREFERENCES/preferences.md and PREFERENCES/context.md — apply them
   to every response (tone, language, level of detail, formats).
4. When Jean says "remember this" or a durable preference emerges, propose
   an update to the relevant file (show the exact edit) instead of relying on
   chat-only memory.
5. At the end of a working session, propose updates to:
   - BUSINESS/status.md (new current state + next steps)
   - BUSINESS/decisions.md (any decision made: date, decision, rationale)
6. Commit messages: imperative, one line, e.g. "Update status: market scan done".
7. Git cadence: commit and push once every FIVE user requests, not after every
   request. Accumulate the changes from the last five requests and batch them
   into a single commit+push on the fifth request. Do not commit or push on
   requests 1-4 of a batch. (This batch rule does not override rule 5: still
   propose status/decisions updates in the session where the work happened.)
8. Write files in plain Markdown. No vendor-specific formats. No secrets.
