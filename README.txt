SYNDOR — Vercel 404 Fix

WHY THE 404 HAPPENS
The uploaded file was named "index (3).html". Static hosting platforms such as Vercel expect the homepage entry file to be named exactly "index.html" in the project root.

DEPLOY
1. Extract this ZIP.
2. In Vercel, create/import a project and upload/connect the extracted project folder (the folder containing index.html and vercel.json).
3. Framework Preset: Other.
4. Build Command: leave blank.
5. Output Directory: leave blank / project root.
6. Deploy, then open the root domain (https://your-project.vercel.app/), not a file name or a stale preview URL.

NOTES
- This is a static front-end prototype.
- Login is demo-only; it does not authenticate against a server.
- Contact and newsletter forms do not transmit or store submissions.
