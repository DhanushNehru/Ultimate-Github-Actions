# Contributing to Ultimate GitHub Actions 🚀

Thank you for your interest in contributing! This list is **community-driven** and thrives on your input. Whether you're adding a new action, fixing a broken link, or improving a description — every contribution helps.

---

## 📋 How to Contribute

### 1. **Find or Add a Resource**
- Browse the [README.md](../README.md) to see current categories.
- If your action fits an existing category → add it there.
- If it doesn't fit → suggest a **new category** (we love fresh ideas!).

### 2. **Fork & Clone**
```bash
git clone https://github.com/<your-username>/Ultimate-Github-Actions.git
cd Ultimate-Github-Actions
```

### 3. **Add Your Entry**

Edit `README.md` and add your action using this exact format:

```markdown
- [action-name](https://github.com/username/action-name) – Short, clear description. ![Stars](https://img.shields.io/github/stars/username/action-name?style=social)
```

**Best Practices**:
- **Keep descriptions ≤ 80 characters**
- **Use active voice**: `Deploys to Vercel` (not "Vercel deployment")
- **Add star badge** if >1k stars (optional but encouraged)
- **Insert alphabetically** within the correct category
- **No trailing spaces or inconsistent punctuation**

**Example**:
```markdown
- [vercel-action](https://github.com/amondnet/vercel-action) – Deploy Next.js apps to Vercel. ![Stars](https://img.shields.io/github/stars/amondnet/vercel-action?style=social)
```

### 4. **Preview Locally (Optional)**

Use any Markdown viewer:
- [Dillinger](https://dillinger.io/)
- VS Code + **Markdown All in One** extension
- `grip` CLI: `pip install grip && grip README.md`

### 5. **Commit & Push**

```bash
git add README.md
git commit -m "feat: add action-name – deploys to Vercel"
git push origin main
```

### 6. **Open a Pull Request**

- **Title**: `feat: add <action-name> to <category>`
- **Description**:
  ```markdown
  Adds [`action-name`](https://github.com/username/action-name) to the **Deployment** category.

  - Deploys web apps with zero-config
  - Supports preview URLs and environment variables
  - Used by 5k+ repos
