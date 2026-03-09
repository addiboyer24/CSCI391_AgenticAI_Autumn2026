# CS 391 — ST: Agentic AI
### University of Montana | Special Topics Course Site

A static course website modeled after [Stanford CS221](https://web.stanford.edu/~cpiech/cs221/index.html), built for GitHub Pages.

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g., `cs391-agentic-ai`).
2. Upload / push all files in this folder to the `main` branch.
3. Go to **Settings → Pages → Source** and select `main` branch, root `/`.
4. Your site will be live at `https://<your-username>.github.io/cs391-agentic-ai/`.

## Customizing

- **Instructor info:** Edit `index.html` — search for `[Your Name]` and replace.
- **Meeting time/room:** Edit the `.hero-meta` paragraph in `index.html`.
- **Schedule:** Update the `<tbody>` of the schedule table in `index.html`.
- **Slide links:** Replace `href="#"` with actual slide PDF/PPTX links.
- **UM Seal:** Drop a `um_seal.svg` or `um_seal.png` into the `img/` folder.
- **Colors:** Tweak CSS variables at the top of `css/style.css`.

## Structure

```
index.html                  ← Main course page (schedule, info, policies)
css/style.css               ← All styles (UM maroon + copper theme)
js/main.js                  ← Minimal JS (year, scroll highlight)
handouts/
  office-hours.html
  python-setup.html
  agent-frameworks.html
  project-guidelines.html
  syllabus.html             ← Placeholder — link your syllabus PDF here
assignments/
  hw1-reflex-agents.html
  hw2-search.html
  hw3-llm-tools.html
  hw4-multiagent.html
  final-project.html
img/                        ← Drop um_seal.svg here
_config.yml                 ← GitHub Pages config (no Jekyll theme)
```

## Textbook Reference

Russell & Norvig. *Artificial Intelligence: A Modern Approach*, **4th edition** (Pearson, 2021).  
ISBN 978-0-13-461099-3 | [aima.cs.berkeley.edu](https://aima.cs.berkeley.edu)
