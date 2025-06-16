# Dev Dashboard Project

Welcome to the **Dev Dashboard** repo...a collaborative learning project by and
for our group!

> **Goal:** Build a unified platform of tools that help us (and eventually
> others!) learn and work together more effectively.

---

## Current Phase: Project Management Board

Our first build is a **Trello-like project management board**. This foundational
tool will help us coordinate all future projects from one place.

## Planned Phases:

- ### Phase 1: Project Management Board
- ### Phase 2: The Idea whiteboard
- ### Phase 3: Notes (Obsidian Lite / Markdown support)
- ### Phase 4: Dev Resources Hub
- ### Phase 5: ???

## Core Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend & Database:** Firebase (Authentication + Firestore)
- **Workflow:** Git & GitHub

---

## Project Team

This project is made possible by these awesome contributors.

### UI/UX & Design Team

- **Remy Francis** (UI/UX Lead) - [remyf870](https://www.github.com/remyf870)

### App Logic & Backend Team

- **Trevor Browning** (Project Lead) -
  [TrevorBrowning](https://github.com/trevorbrowning)
- **Prince Akakpo** - [pope](https://github.com/thesyntaxdude)

---

## Git & GitHub Basics for Beginners

If you're new to Git or GitHub, start here! This guide walks you through setup,
concepts, and our contribution workflow.

---

### Part 1: One-Time Setup

#### A. Install Git

Download Git from the official site:  
[https://git-scm.com/downloads](https://git-scm.com/downloads)

#### B. Configure Git

Open your terminal (Mac: `Terminal`, Windows: `Git Bash`) and set your Git
identity. Use the same email as your GitHub account:

```
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

### Part 2: Core Vocabulary

| Term                  | Description                                                                                 |
| --------------------- | ------------------------------------------------------------------------------------------- |
| **Repository (Repo)** | A folder with your project code + its full change history.                                  |
| **Commit**            | A snapshot of your code. Like a save point with a message.                                  |
| **Branch**            | A separate version of the code — lets you safely work on features without affecting `main`. |
| **Pull Request (PR)** | A request to merge your branch into `main`, with a review by others.                        |

---

### Part 3: Contribution Workflow

> Follow these steps each time you want to contribute to the project.

---

### Step 0: Get the Latest Code

Always start by syncing with the latest version of the project:

### Switch to the main branch

```
git checkout main
```

### Get the latest updates

```
git pull origin main
```

### Step 1: Choose an Issue & Create a Branch

1. Go to the **Issues** tab on the Repo's GitHub.
2. Assign yourself an issue that is open and you'd like to work on.
3. Create a new branch named after your task:

```
git checkout -b feature/login-button-style
```

_Format: \`branch-type/short-description\` (e.g., \`bug/fix-header\` or
\`feat/add-auth\`)_

---

### Step 2: Do the Work (Add + Commit Cycle)

## While working:

# Stage changes

### Add all changed files

```
git add .
```

### (Optional: add specific files)

```
git add file.js
```

# Commit changes with a clear message

Example:

```
git commit -m "feat: Add login button style"
```

Repeat the \`add + commit\` cycle as needed until your work is done.

---

### Step 3: Push Your Branch to GitHub

Once you're finished coding:

```
git push --set-upstream origin your-branch-name
```

Example: git push --set-upstream origin feat/ChangeREADME

This uploads your branch to the GitHub repo. You only need to do this once
before opening a pull request.

---

### Step 4: Open a Pull Request (PR)

1. Visit the repo on GitHub.
2. You'll see a banner offering to compare & pull request — click it!
3. Fill in:
   - **Title** (e.g., \`feat: Add login styling\`)
   - **Description** — what you did & why
   - Mention the issue: \`Closes #3\` (automatically links & closes it)
4. Click **Create Pull Request**

---

### Step 5: Review, Feedback & Merge

Team members will now:

- Review your code
- Leave comments or request changes
- You update your branch and \`push\` again if needed

Once approved, your PR will be merged into the \`main\` branch of the project.

---

**Congrats! Your code is now part of the project.**

Now you can:

### Return to main branch

```
git checkout main
```

### Sync latest changes

```
git pull origin main
```

Pick your next issue and repeat the cycle!

---

## Tips for Success

- Keep commit messages clear and descriptive (\`feat:\`, \`fix:\`, \`refactor:\`
  prefixes help!)
- Ask questions — we’re all here to learn together.
- Use branches for _every_ feature or fix.
