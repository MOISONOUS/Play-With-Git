# Play-With-Git

A single-page interactive Git cheat sheet with visual diagrams, built as a self-contained HTML file — no build step, no dependencies, no server required.

## What's inside

**10 command sections** covering the full Git workflow:

| Section | Commands covered |
|---|---|
| Setup & Config | `git config`, `git help` |
| Creating Repositories | `git init`, `git clone` |
| Staging Area | `git add`, `git diff`, `git rm / git mv` |
| Committing | `git commit`, `git log`, `git show` |
| Branching | `git branch`, `git checkout / switch`, `git stash` |
| Merging & Rebasing | `git merge`, `git rebase`, `git cherry-pick` |
| Remote Repositories | `git remote`, `git fetch`, `git pull`, `git push` |
| Undoing Changes | `git restore`, `git reset`, `git revert`, `git clean` |
| Inspection & History | `git status`, `git blame`, `git bisect` |
| Tags & Advanced | `git tag`, `git reflog`, `git submodule`, `git worktree` |

Each command includes:
- A short description explaining what the command actually does
- Practical examples with notes
- An SVG diagram visualizing the operation

## Features

- **Collapsible sidebar** with section navigation and live search
- **Scroll spy** — sidebar highlights the section currently in view
- **Copy to clipboard** on every command example
- **Tooltips** on diagram elements
- **Jump-to-card** highlights the card in its section color when navigating from the sidebar

## Usage

Open `git-cheatsheet.html` directly in a browser. No installation needed.

```
open git-cheatsheet.html   # macOS
start git-cheatsheet.html  # Windows
xdg-open git-cheatsheet.html  # Linux
```

## Design

Warm dark terminal aesthetic — JetBrains Mono, flat cards with per-section left-border accents, no box shadows, 2px border radius. Each of the 10 sections has its own accent color that propagates through its sidebar entry, section header, card borders, and diagram highlights.
