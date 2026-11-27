Theme variants added on branch: theme/retro-cyberpunk-variants

Files included:
- index.retro.html — Retro Terminal theme (green-on-black, monospace, CRT scanlines, typing micro-animation).
- index.cyberpunk.html — Cyberpunk / Synthwave theme (neon magenta/cyan accents, animated gradients, bold hero text).

How to view locally:
1. Checkout the branch:
   git fetch origin
   git checkout theme/retro-cyberpunk-variants

2. Serve files locally (simple HTTP server):
   python3 -m http.server 8080
   Open http://localhost:8080/index.retro.html and http://localhost:8080/index.cyberpunk.html to compare.

Notes:
- These are non-destructive variant files; your existing index.html is unchanged.
- If you want both themes in a single page with a toggle, I can update index.html instead.

Next steps I can take for you:
- Open a pull request to merge this branch into copilot/research-portfolio-structure (recommended for review).
- Add a live theme toggle implementation to index.html (if you prefer a single file).
