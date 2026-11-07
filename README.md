# portfolio-optimization

Code, research and weekly updates for the St. George Capital Optimization Team.

We take the prediction team's forecasts and turn them into portfolios the fund can actually trade, and then check whether those portfolios hold up.

| | Project | Goal |
|---|---|---|
| **Project 1** | Portfolio Optimization | Given forecasts, build the best portfolio the fund can actually trade |
| **Project 2** | Risk & Backtesting Tool | Given any portfolio, explain what's risky about it and how to fix it |

---

## Repo structure

```
├── project1/      # Portfolio Optimization
├── project2/      # Risk & Backtesting Tool
├── data/          # Your local data files. Gitignored, never pushed
├── requirements.txt
└── README.md
```

- Work inside your own project's folder.

---

## Getting started

1. **Clone the repo** (once):
   ```bash
   git clone <repo-url>
   cd <repo-name>
   ```
2. **Create a virtual environment and install packages:**
   ```bash
   python -m venv .venv
   source .venv/bin/activate        # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. **Put any data files in `data/`.** They stay on your computer and are never pushed.

---

## How we work

### Code → Branches and pull requests
- `main` is protected. **Never push straight to main.**
- One branch per task, named after the project:
  - `p1/hrp`, `p1/black-litterman`
  - `p2/stress-tests`, `p2/factor-exposures`
- When it's ready, open a **pull request** and get **one teammate's review** before merging.

### Weekly updates → Discussions
Post updates in your Discussions category: **Project 1 Updates** or **Project 2 Updates**.

```
Done:
Next:
Blockers:
```

---

## Git crash course

A **commit** is a save point. A **branch** is a parallel copy. A **pull request** asks to merge your branch into main.

| Command | What it does |
|---|---|
| `git pull` | Get your teammates' latest changes |
| `git switch -c p1/hrp` | Start a branch for your task |
| `git status` · `git diff` | See what you changed |
| `git add .` · `git commit -m "msg"` | Save a snapshot with a short message |
| `git push -u origin p1/hrp` | Upload your branch, then open a pull request |

New to git? Do [Learn Git Branching](https://learngitbranching.js.org) (about an hour) before your first pull request.
