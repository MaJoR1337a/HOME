<!--
  Brief, repository-specific instructions for AI coding agents (Copilot-style).
  Keep these short and actionable — they should help an AI be immediately useful in this repo.
-->

# Copilot / AI agent instructions — HOME

Summary
- This is a tiny static website (single-page HTML) at `index.html` used for a simple landing page.

What matters most
- Preserve the page content (Ukrainian copy, contact info in footer) unless user asks to change it.
- Keep output minimal and focused — this repo contains no build system, tests, or server code.

Key files
- `index.html`: single source of truth. Fix HTML semantics, casing, and accessibility issues here.

Common, discoverable patterns and examples
- This page contains several malformed or inconsistent HTML tags you can correct. Examples to target:
  - Wrong casing: use lowercase tags (replace `uL`, `lI`, `P` with `ul`, `li`, `p`).
  - Misspelled tags: replace `arcitcle` with `article`.
  - Keep anchor hrefs intact unless the user requests link changes — e.g., `mailto:zadorozhniy1998@gmail.com` and phone `tel:+380997472008` in the footer must remain untouched unless asked.

Editing & PR guidance for AI
- Make minimal, well-explained edits: change one class of issues per commit (e.g., fix tag casing in one PR).
- Use semantic HTML and accessible attributes (e.g., ensure headings are in logical order, add alt text for images if added).
- Do not invent or remove real contact information; ask for confirmation before adjusting personal/identifying data.

Local verification
- There's no build step — preview changes by opening `index.html` in a browser or run a local server:
  - PowerShell: `python -m http.server 8000` then open http://localhost:8000

When to ask for guidance
- If the change affects copy (Ukrainian text) or contact details, ask the user before modifying.
- If a new asset (images/CSS) is required, propose a small plan and request approval before adding files.

Examples of acceptable quick fixes
- Normalize HTML tag casing and correct misspellings (e.g., `uL` → `ul`, `lI` → `li`, `arcitcle` → `article`).
- Improve semantic headings or add missing `meta` attributes for accessibility/meta description — but query for copy changes.

Do NOT do
- Remove or change contact info without explicit permission.
- Add major functionality or restructure the project without approval — propose changes first.

If you need more context
- Ask for: (1) editorial direction for content changes, (2) whether personal contact info may be updated, (3) preferred styling or new assets.

— End of instructions —
