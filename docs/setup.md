# Friction Log Setup Guide

This guide explains how to enable GitHub Discussions, add a friction-report template, and set up contribution flows and badges for a developer friction log.

---

## ✅ Enable GitHub Discussions

1. Go to your repository.
2. Click **Settings** → **Features** → Check the box for **Discussions**.
3. Go to the new **Discussions** tab and create a **category** named `Frictions`.

---

## 🧵 Add a Pinned Discussion

In the **Discussions > Frictions** category, create a new post and pin it.

**Title:** How to Share Developer Frictions  
**Body:**

```markdown
Welcome to the Developer Friction Log!

This space is for developers to share real-world points of friction in their workflow—things that slow you down, confuse you, or just make development less joyful.

### What counts as friction?
- It takes too long to set up a new repo
- I can’t find documentation for internal tools
- CI fails with unclear error messages

### How to Contribute:
1. **Start a new Discussion in this category**
2. **Join existing threads**
3. **We may convert some frictions to GitHub Issues**

Thank you for contributing to a better developer experience!
```

---

## 📄 Add a Discussion Template

Place the following file in:

```
.github/DISCUSSION_TEMPLATE/friction-report.md
```

**Content:**

```markdown
---
name: Friction Report
about: Share a developer experience issue you're encountering
labels: friction
---

## 🧩 What were you trying to do?

> Describe the task or goal you were working on when you encountered friction.

---

## 🔍 What got in the way?

> Explain the specific issue, slowdown, confusion, or blocker.

---

## 🔧 How did you work around it? (Optional)

> Share any temporary solution, workaround, or hack you used.

---

## 💡 Suggested Improvement or Fix (Optional)

> If you have thoughts on how this could be improved, include them here.
```

---

## 📊 Add GitHub Badges

Add these badges to the top of your `README.md`:

```markdown
[![Discussions](https://img.shields.io/github/discussions/YOUR-USERNAME/YOUR-REPO?style=flat-square)](https://github.com/YOUR-USERNAME/YOUR-REPO/discussions)
[![Issues](https://img.shields.io/github/issues/YOUR-USERNAME/YOUR-REPO?style=flat-square)](https://github.com/YOUR-USERNAME/YOUR-REPO/issues)
```

Replace `YOUR-USERNAME/YOUR-REPO` with your actual repo path.
