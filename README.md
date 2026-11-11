# tk-gui-demo

The GUI demo for [cleanroom](https://github.com/amanvicky/cleanroom) — paste this repo's
URL into [the live runner](https://amanvicky.github.io/cleanroom/) and:

- **`run gui_notes.py`** — the tkinter notes app opens on the **app screen** as real HTML
  widgets (virtual tkinter: a subset; skipped extras are counted in the terminal).
- **`preview`** — `index.html` (a plain notes web app) opens in a **sandboxed frame**:
  scripts run, but the frame has no origin, no storage, no network.
- **this PC** mode: `serve python -m http.server 8000 --bind 127.0.0.1` serves that web
  app as a real process on your machine; click the printed port chip to use it, then
  **Stop** and **wipe** — residue 0.

Both apps are deliberately boring: no network, no secrets, nothing scored by triage.
