---
name: Release Checklist
about: Track tasks for a new release
title: "Release vX.X.X"
labels: [release]
---

## 📦 Release vX.X.X

### ✅ Pre-Release
- [ ] Update changelog
- [ ] Bump version in code
- [ ] Run tests
- [ ] Tag release in Git

### 🚀 Deployment
- [ ] Build and push Docker image
- [ ] Deploy to staging
- [ ] Verify staging

### 🏁 Post-Release
- [ ] Deploy to production
- [ ] Verify production
- [ ] Announce release (Slack, Email, etc.)
- [ ] Archive old release notes
