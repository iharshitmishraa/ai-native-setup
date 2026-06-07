# AI-Native Dev Environment Setup
An AI-assisted coding setup on Windows: Cursor as the editor, with Claude Code
and Codex running inside it as AI agents, plus Git and GitHub for version
control. This is a short log of what I installed, the steps I took, and how it
went.
Tools installed

Cursor — VS Code-based editor, used as the base for both AI agents.
Claude Code (Cursor extension) — Anthropic's coding agent. Signed in with
my Anthropic account.
Codex (Cursor extension) — OpenAI's coding agent. Signed in with my
OpenAI account.
Git + GitHub — version control and remote hosting.

Platform: Windows.
Steps I took

Installed Cursor from cursor.com and opened it.
Added the Claude Code extension from the Extensions panel and signed in. Sent
it a quick test prompt to confirm it was actually responding, not just
showing as installed.
Added the Codex extension the same way and signed into my OpenAI account,
then gave it a test prompt too.
Created a new public repository on GitHub with a README.
Cloned the repo into Cursor so I could edit it locally.
Wrote this README, then committed and pushed it back to GitHub.

Issues and how I handled them
The setup ran clean, so I won't pad this out. Both extensions installed and
logged in on the first try, and Git was already working on my machine. No
blockers.
The two things I made a point of checking instead of assuming:

That each agent was actually live, not just installed. "Installed" and
"authenticated and responding" aren't the same thing, so I sent a small test
prompt to both Claude Code and Codex and confirmed each returned a real
answer tied to the right account.
The GitHub round-trip. Since I created the repo on the web first, I cloned
it into Cursor, edited locally, then committed and pushed. After pushing I
reloaded the repo page to confirm the README had updated, rather than assuming
the push went through.

Notes
Having Claude Code and Codex side by side in one editor makes it easy to send
the same prompt to both and compare answers before trusting either one. That
cross-check is the main reason I'd keep both installed rather than picking just
one.
