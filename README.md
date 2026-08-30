# FAST — Finger Accuracy Speed Trainer

A typing trainer built for people who don't type with ten fingers on home row — because the standard method doesn't fit every hand. Rewrite a passage, watch your mistakes in red and your progress in green, then race your own clock until your own style becomes fast.

**Open `index.html` in any browser. That's the whole install.** No build step, no server, no account, no internet connection required after the first load.

---

## Why this exists

I'm Mohamed — Cheikh — and I built FAST because the typing advice everyone gives assumes hands that work like everyone else's. Mine don't. I ended up teaching myself a 2–4 finger method that actually fits how I type, and I built this site to practice it — and to let anyone else with the same problem do the same.

The full story is written into the site itself — open it and click **"The story behind FAST"** in the top navigation.

---

## Features

- **Practice by rewriting real text** — a built-in climate-change essay to start, or paste your own passage (saved locally for next time).
- **Live, non-blocking feedback** — every character lights up green when correct or red when wrong, but a mistake never stops you. Keep typing at your own pace, and press `Backspace` any time to go back and fix something before you finish.
- **A full session report** — net WPM, gross WPM, final accuracy, raw keystroke accuracy, mistakes you fixed vs. mistakes still on the page, and how this run compares to your personal best on that text.
- **Beat-your-own-clock challenges** — after a run, set a tighter target (−10s, −20s, or a custom margin) and retype the same passage against it. Miss the goal, and the report lets you loosen the timer and try again instead of just failing.
- **Five built-in themes** — Graphite, Paper, Midnight, Forest, and Ember — switchable from the header and remembered between visits.
- **Fully offline** — everything runs client-side. All settings, saved texts, personal bests, and history live in your browser's `localStorage`; nothing is ever uploaded anywhere.
- **Built for a physical keyboard** — FAST is a desktop/laptop tool. On small screens it shows a notice instead of the trainer, since the whole point is practicing real keyboard technique.

---

## How to use it

1. Open `index.html`.
2. Start with the built-in essay, or paste your own text to practice.
3. Type. Correct letters turn green, mistakes turn red — keep going, and use `Backspace` if you want to go back and clean one up before you reach the end.
4. When you finish, read your report: time, WPM, accuracy, and how many mistakes you cleaned up vs. left behind.
5. Set a challenge — pick a time margin and retype the same passage against a tighter clock.
6. Switch themes any time from the top-right of the page.

---

## Tech

Plain HTML, CSS, and vanilla JavaScript in a single file. No frameworks, no build tools, no external fonts or scripts loaded over the network — so it keeps working even with no connection at all.

---

## Roadmap ideas

- A history page showing progress over time (the data is already being saved, just not displayed yet)
- Difficulty-adjusted texts (short quotes, code snippets, longer articles)
- Per-finger heatmaps for the 2–4 finger method specifically

Ideas and issues are welcome — this project is meant to grow with the people who actually use it.

---

## Author

**Mohamed Cheikh** ("MC88")
GitHub: [mohamed005cheikh-rgb](https://github.com/mohamed005cheikh-rgb)
Email: mohamed005cheikh@gmail.com
WhatsApp: +222 30 72 64 75

© Mohamed Cheikh. All rights reserved.
