🔹 Initialize & First Push (Local → GitHub)

```bash
git init
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

---

### 🔹 Add Files

```bash
git add <file-name>
git add <file1> <file2>
git add .
git add -A
```

---

### 🔹 Commit

```bash
git commit -m "message"
git commit -am "message"
```

---

### 🔹 Push (Local → GitHub)

```bash
git push
git push origin main
```

---

### 🔹 Pull (GitHub → Local)

```bash
git pull
git pull origin main
```

---

### 🔹 Sync Local with Remote (Safe)

```bash
git fetch origin
git merge origin/main
```

---

### 🔹 Clone Repo (GitHub → Local)

```bash
git clone https://github.com/<username>/<repo-name>.git
```

---

### 🔹 Check Status & History

```bash
git status
git log
git log --oneline
git branch
```

---

### 🔹 Branch Commands

```bash
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git merge <branch-name>
git branch -d <branch-name>
```

---

### 🔹 Remote Commands

```bash
git remote -v
git remote remove origin
git remote set-url origin <new-url>
```

---

### 🔹 Undo / Fix

```bash
git restore <file>
git reset <file>
git reset --soft HEAD~1
git reset --hard HEAD~1
```

---

### 🔹 Stash

```bash
git stash
git stash pop
git stash list
```

---

### 🔹 Tags

```bash
git tag v1.0.0
git push origin v1.0.0
```

---

### 🔹 Force / Rebase (Advanced)

```bash
git push --force
git pull --rebase
```

---

### 🔹 Clean

```bash
git clean -fd
```

---

### 🔹 Configure (Once)

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

---

If you want:

* **Cheat-sheet image**
* **Beginner-safe subset**
* **Professional Git workflow (PR-based)**

say the word.
