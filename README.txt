TOP COMMITTEE PORTAL — PROTOTYPE v0.1

Open index.html in a modern browser, or visit http://127.0.0.1:4173 while the local preview server is running.

To restart the preview from this directory:
python3 -m http.server 4173 --bind 127.0.0.1

Included:
- Three committee workspaces: Group ITLT, Global ITLT and K-DD.
- Session creation and editing, dates, chairs, meeting locations and status.
- Agenda topics with owners, presenters, descriptions and readiness status.
- Upload, download and remove protocols, slides and supporting materials.
- Session briefings with editable sections, agenda-based draft and text export.
- Decisions/actions with owners, due dates and completion status.
- Committee filters, search and responsive layouts.

Data is saved locally in this browser: localStorage for workspace records and IndexedDB for file contents. Use the same browser and address to retain access to your data. Clearing browser data removes the prototype's data. There is no shared database, user authentication, committee access enforcement or approval routing yet. The three levels are displayed as supplied, without escalation rules. Sample topics and sessions are illustrative.

The briefing draft uses agenda metadata. It does not read or summarize uploaded PDF, PowerPoint or Word contents. Review the draft before saving. Downloaded briefings contain your saved text.

No installation or build is required. The app works without external scripts. Optional Google Fonts fall back to system fonts when offline.

Source: index.html, style.css, app.js. Keep these files together.

App name: Top Committee Portal. Suggested GitHub repository name: top-committee-portal.
