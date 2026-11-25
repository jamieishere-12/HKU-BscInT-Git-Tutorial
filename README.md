# HKU BscInT Git & GitHub Tutorial

Welcome! Follow these steps in **VS Code** to practice branching, committing, pushing, and pulling.

## Part 1: Setup (First-Time Users Only)
1. Open the terminal in VS Code (`Ctrl + ~` or top menu: **Terminal → New Terminal**).
2. Set your Git name and email (use the same email as your GitHub account):
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your-email@connect.hku.hk"
   ```

## Part 2: Clone, Branch & Edit
1. In VS Code, click the **Source Control** icon on the left sidebar → **Clone Repository**.
2. Paste `https://github.com` and save it to your Desktop, then click **Open**.
3. Click **`main`** in the very bottom-left corner → **`+ Create new branch...`** → name it `student-yourname`.
4. Open `index.html`, add a new line `<li>Your Name - Hello World!</li>` inside `<ul>`, and save (`Ctrl+S` / `Cmd+S`).

## Part 3: Commit, Push & Pull Request
1. Click the **Source Control** icon on the left sidebar.
2. Type a message (e.g., `Add my name`) in the box and click **Commit** (click **Yes** if asked to stage changes).
3. Click **Publish Branch**:
   - Sign into GitHub when VS Code prompts you.
   - When VS Code asks *"Would you like to create a fork and push to it instead?"*, click **Create Fork**.
4. Click **Create Pull Request** (in VS Code or on GitHub) to submit your work!

## Part 4: Pull Everyone's Combined Work
After the lecturer merges the Pull Requests on screen, switch back to `main` (bottom-left corner) and run this in the VS Code terminal to see everyone's names:
```bash
git pull https://github.com main
```
