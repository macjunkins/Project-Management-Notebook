# Using Obsidian for a Dev Notebook

**Purpose:** Organize your dev logs, ideas, and app architecture documentation.

## 1. **Setup**

- Download from: [https://obsidian.md](https://obsidian.md/)

- Create a vault for dev work (e.g., `~/Documents/DevVault`)

- Turn on "Daily Notes" and "Templates" plugins in _Settings > Core Plugins_

### 2. **Folder Suggestions**

- `📓 Daily Logs`

- `🧠 Ideas & Concepts`

- `📦 MVP Plans`

- `🔧 Code Snippets`

- `🧪 Experiments`

- `🗂️ Project Docs`

### 3. **Starter Templates**

Use templates to standardize logs:

markdown

Copy code

`# {{date}} – Dev Log ## ✅ Goals -  ## 💻 What I Did -  ## 🧠 Thoughts -  ## 🛠 Problems/Solutions -`

### 4. **Best Practices**

- Use backlinks (`[[note name]]`) to connect ideas

- Use tags (`#mvp`, `#bug`, `#idea`) for filtering

- Sync across devices (Obsidian Sync or iCloud Drive)

## 🧠 **Obsidian + GitHub**

**Use Case:** Version control your notes, back them up to GitHub, and optionally sync across devices.

### 1. **Set Up GitHub Integration**

- Initialize your Obsidian vault as a local Git repo:

    bash

    Copy code

    `cd ~/Documents/DevVault git init git remote add origin https://github.com/YOUR_USERNAME/dev-notes.git`

### 2. **Commit Notes**

In Warp or VS Code:

bash

Copy code

`git add . git commit -m "Update dev notes" git push origin main`

### 3. **Recommended Plugin**

- [Obsidian Git](https://github.com/denolehov/obsidian-git): Automates backups, commits, and pulls.

  - Configure: `Settings → Plugin Options → Obsidian Git`

---
