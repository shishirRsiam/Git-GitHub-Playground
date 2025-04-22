## 🧾 GIT CHEATSHEET (Printable)

### 🔧 CONFIGURATION
```
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
```

---

### 📁 CREATE / CLONE
```
git init                      # Create new repo
git clone <repo-url>         # Clone existing repo
```

---

### 📄 STAGING & COMMITTING
```
git status                   # View changes
git add <file>               # Stage a file
git add .                    # Stage all files
git commit -m "message"      # Commit staged files
git commit -am "message"     # Stage + commit tracked files
```

---

### 🔁 BRANCHING
```
git branch                   # List branches
git branch <name>            # Create branch
git checkout <name>          # Switch branch
git checkout -b <name>       # Create + switch
git merge <name>             # Merge branch into current
git branch -d <name>         # Delete branch
```

---

### 🚀 PUSH / PULL
```
git push                     # Push current branch
git push -u origin <branch>  # Push and track
git pull                     # Pull latest changes
git fetch                    # Fetch remote changes
```

---

### 🌐 REMOTE
```
git remote -v                # Show remotes
git remote add origin <url>  # Add remote
git remote remove origin     # Remove remote
```

---

### 🔍 LOG & HISTORY
```
git log                      # Full commit log
git log --oneline            # One-line summary
git show <commit-id>         # Show commit details
```

---

### 🧹 RESET / UNDO
```
git checkout -- <file>       # Discard changes
git reset HEAD <file>        # Unstage file
git reset --hard             # Reset all to last commit
```

---

### 📦 STASH
```
git stash                    # Save changes temporarily
git stash pop                # Reapply saved changes
```

---

### 🏷️ TAGGING
```
git tag                      # List tags
git tag <name>               # Create tag
git push origin <tag>        # Push tag
```

---

