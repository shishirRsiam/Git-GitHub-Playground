## 🚀 Advanced GitHub Topics

### 1. **GitHub Actions (Advanced)**
- ✅ **Matrix Builds**: Test across multiple versions/platforms.
- ✅ **Reusable Workflows**: Create DRY pipelines you can call from multiple repos.
- ✅ **Artifacts & Caching**:
  - Use `actions/cache` to speed up workflows.
  - Save test reports/builds with `upload-artifact`.
- ✅ **Manual Triggers (workflow_dispatch)**:
  - Trigger workflows on demand from the GitHub UI.
- ✅ **Environment Secrets & Approvals**:
  - Protect prod deployments with manual approval gates.
- ✅ **Deploy to Multiple Environments**: (staging → prod)
- ✅ **Security Scans**:
  - Use `codeql`, `trivy`, or `bandit` for automated scanning.

---

### 2. **GitHub Packages & Container Registry**
- Publish and use Docker images via:
  - `ghcr.io/username/image-name`
- Useful for internal microservices or custom CLI tools.

---

### 3. **GitHub CLI (gh)**
- Automate issues, PRs, CI/CD pipelines from terminal:
```bash
gh pr create --base main --head feature --title "New Feature"
```

---

### 4. **GitHub Advanced Security**
> (Paid feature on GitHub Enterprise, but worth knowing)
- Secret scanning
- Code scanning (CodeQL)
- Dependency review

---

### 5. **Git Submodules & Git Subtrees**
- For managing monorepos or shared libraries between projects.

---

### 6. **Monorepo Strategy**
- Manage frontend + backend + infra in a single repo.
- Use `path:` filters in workflows to trigger only parts of the repo.

---

### 7. **GitHub Webhooks**
- Trigger external services (e.g., Slack, Discord, Jenkins) based on repo activity.

---

### 8. **Custom GitHub Apps & Bots**
- Write bots that auto-respond, tag issues, approve PRs, or do anything via GitHub API.

---

### 9. **Protected Branch Rules**
- Enforce PR reviews, successful builds, linear history, etc.
- Great for team collaboration & open-source work.

---

### 10. **Template Repositories & Starter Workflows**
- Create boilerplates others can fork with all CI/CD and structure in place.

---

Would you like:
- A hands-on project using these?
- Or specific examples (e.g., setting up a matrix build with test + deploy steps)?
- Or maybe a list of **interview-level** GitHub topics?
- Or **best practices** for using GitHub in teams?