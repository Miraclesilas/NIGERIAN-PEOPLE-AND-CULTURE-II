# GST 121 — Nigerian People & Culture CBT Practice

A single-page CBT practice app for University of Uyo GST 121.

## Features
- 200 objective practice questions.
- Randomized question selection.
- Time and question-count controls.
- New accounts receive 50-question access pending approval.
- Admin approval unlocks all 200 questions.
- Sign-up/sign-in modal with username and password; email is optional for profile.
- Unanswered indicator and per-question flags.
- Local attempt history and percentage performance.
- Profile editing and score sharing.
- Submission animation, percentage ranking and a retry message below 30%.
- Admin portal for approval/revocation and deletion.
- University/author footer attribution.

## Important source note
The question bank is original practice material based on the documented University of Uyo GST 121 themes and publicly verifiable descriptions of the 2024 textbook. It is not a reproduction of the copyrighted textbook. For exact page-by-page coverage, the official textbook PDF should be supplied.

## Security
This is a static GitHub Pages/local-browser demo. Client-side authentication is NOT secure because credentials and application data can be inspected in browser source. For production use, replace the demo authentication with server-side authentication and role-based access control (for example, Supabase/Firebase/a secure backend), hash passwords, and keep admin credentials server-side.

## GitHub Pages
Upload `index.html`, then enable GitHub Pages from the repository's Pages settings. `index.html` is the complete app.

## Files
- `index.html` — complete application
- `questions.json` — editable 200-question bank
- `README.md` — deployment and security notes
- `LICENSE` — MIT license
