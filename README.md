# Copilot Workshop — Starter Repo

This is the starter repository for the **AI-Assisted Development Workshop Series**. Each session uses this repo as your working environment. You will build real, working outputs here that you own and can keep after the workshop ends.

---

## Getting Started

### First time setup

1. Clone this repository to your machine:
   ```
   git clone [repo URL]
   ```
2. Open the cloned folder in VS Code:
   **File → Open Folder → select the folder → Open**

3. Confirm GitHub Copilot is active — look for the Copilot icon in the bottom status bar. If it shows **Sign In**, sign in with your GitHub account.

That's it. Each session folder below has its own setup instructions.

---

## Sessions

### Session 1 — Intro to GitHub Copilot
**Folder:** repo root  
**What you'll build:** Your first Copilot-assisted code, starting from this README.  
**Setup:** Just VS Code and GitHub Copilot. No additional packages needed.

---

### Session 2 — Prototyping for Non-Developers
**Folder:** `track-b/`  
**What you'll build:** A data notebook that queries, transforms, and visualises retail order data using GitHub Copilot.

**Additional setup before Session 2:**

Pull the latest changes from the repo:
```
git pull
```

Then open the Command Palette in VS Code (`Ctrl+Shift+P` / `Cmd+Shift+P`), type **Python: Create Environment**, select **Venv**, and select your Python installation. VS Code will install the required packages from `requirements.txt` automatically.

**Files:**
- `requirements.txt` — required Python packages (pandas, matplotlib)
- `track-b/orders.csv` — the dataset used in the lab
- `track-b/analysis.ipynb` — your starter notebook

---

## How Copilot Works in This Repo

Copilot reads the files you have open and uses them as context for its suggestions. A few things worth knowing:

- **In `.py` files and notebooks:** type a `#` comment describing what you want, wait 2 seconds, and Copilot will suggest the code. Press **Tab** to accept, **Escape** to dismiss.
- **In VS Code chat (Copilot Chat):** press `Ctrl+Shift+I` to open the chat panel and ask questions or request changes in plain English.
- **Suggestions reflect your context:** the more specific your comment, the more accurate the suggestion. Describe the *what* and *why*, not just the *how*.

---

## Repo Conventions

- **Don't delete starter files.** Each session's materials are intentionally minimal — that's by design.
- **Commit your own work as you go.** Your commits are yours. If you want to save a working state, `git add . && git commit -m "your message"` at any point.
- **Each session builds on the last.** Materials reference concepts and tools introduced in prior sessions.

---

## Need Help?

- Copilot not showing suggestions → click the Copilot icon in the status bar and confirm it shows **Ready**
- Python environment issues → see the setup guide in your session participant materials
- Anything else → ask your facilitator

