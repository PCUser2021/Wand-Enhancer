# AI-Assisted Work Log (Public-Safe)

This log records non-sensitive summaries of repository maintenance performed with AI assistance. Verbatim user prompts and private conversation details must remain in the private central archive; never paste them here.

## 2026-10-22 — Add cross-session context recovery policy

- Added a required section to `AGENTS.md` directing AI-assisted repository work to restore context from current source and the private prompt archive, archive each repo-related prompt privately, and record outcomes after work.
- Established this file for public-safe summaries of implementation work. No verbatim prompt text or credentials are stored in this public repository.
- Verification: the GitHub contents API accepted the `AGENTS.md` update. The commit was returned by GitHub. No build or runtime tests were run because this is a documentation-only policy change.
- Limitation: this does not install a ChatGPT-wide event hook; sessions must load repository instructions and have access to the private archive.
