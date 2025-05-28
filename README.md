# 🧱 Developer Experience Friction Log

Welcome to the **Developer Experience Friction Log**, part of our larger initiative to create a **delightful, productive, and modern engineering environment** for all teams.

## 🎯 Purpose

This friction log serves as a **transparent, ongoing record** of challenges that engineers encounter across our development ecosystem. Inspired by open source best practices, this log helps us:

- Identify and surface pain points experienced by developers
- Encourage open discussion and context sharing across teams
- Quantify and prioritize friction points in our weekly DevEx Advisory reviews
- Collaborate with the right teams to **remove, reduce, or resolve friction**

This is **not** about blame — it's about making our platform better for everyone.

---

## 🙋‍♀️ How to Participate

We want **every engineer** to feel empowered to raise concerns — whether you're onboarding a new service, debugging flaky pipelines, requesting access to tools, or working around documentation gaps.

---

## 🧩 How to Contribute Frictions

We welcome all developers to contribute to our Developer Friction Log!

### 🗣️ Start a Discussion
If you're experiencing a developer friction—or just want to share a DX pain point—start a new [Discussion](https://github.com/ericchapman80/friction-log-starter/discussions) under the **Frictions** category. This allows for open-ended conversation, collaborative brainstorming, and community voting.

- Use a descriptive title (e.g., "Long CI/CD Times on Small Changes")
- Include context (what you were trying to do, expected behavior, what got in your way)
- Others can jump in, add details, or propose solutions

Once a friction is well-understood, we may convert the discussion into a formal GitHub Issue for tracking and resolution.

### 🐞 Create a GitHub Issue
If you already know the friction and want to log it formally, head over to [Issues](https://github.com/ericchapman80/friction-log-starter/issues) and use the **Friction Log Entry** template. You can tag it with relevant labels (e.g., `cognitive-friction`, `access-friction`, `delivery-friction`, etc.) to help us organize themes and trends.

### 🔄 Workflow Summary:
1. **Start with a Discussion** for open feedback.
2. **We'll convert it to an Issue** if it's actionable.
3. **We tag and track issues** in the friction log.

Your contributions help improve developer experience for everyone—thank you!

---

## 🧩 Friction Issue Template

```
### 😖 What’s the friction?

_Describe what’s hard, broken, missing, or confusing._

### 📍 Where did this happen?

_Tool, repo, system, team, etc._

### 🧠 Workarounds or mitigation?

_Did you find a workaround? What failed?_

### ⏱️ Time lost or productivity impact

_Estimate (if known)._

### 💡 Any suggestions?
```

---

## 🚀 What Happens Next

- All submissions are reviewed by the **DevEx Technical Advisory Group** during our weekly meeting.
- Items will be:
  - Clarified if needed
  - Tagged by category (e.g., pipelines, access, onboarding, tooling)
  - Prioritized by impact and effort
- We will track status updates and resolutions transparently via GitHub.

---

## 🔧 Setup Instructions

To enable full contribution flow via Discussions and Issues, follow these steps.

### ✅ Enable GitHub Discussions

1. Go to your repository.
2. Click **Settings** → **Features** → Check the box for **Discussions**.
3. Go to the new **Discussions** tab and create a **category** named `Frictions`.

### 📌 Create a Pinned Discussion

Use this post to guide contributors:

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

### 🗂️ Add the Discussion Template

Create this file at:

```
.github/DISCUSSION_TEMPLATE/friction-report.md
```

With this content:

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

### 📊 Add GitHub Badges

Paste these badges at the top of your `README.md` to highlight activity:

```markdown
[![Discussions](https://img.shields.io/github/discussions/YOUR-USERNAME/YOUR-REPO?style=flat-square)](https://github.com/YOUR-USERNAME/YOUR-REPO/discussions)
[![Issues](https://img.shields.io/github/issues/YOUR-USERNAME/YOUR-REPO?style=flat-square)](https://github.com/YOUR-USERNAME/YOUR-REPO/issues)
```

Replace `YOUR-USERNAME/YOUR-REPO` with your actual repository path.

---

## 🧭 Guiding Principles

- We value **engineer experience as a product**
- Friction is often a signal, not a failure
- Collaboration and empathy across teams will help us build something great
- This log is a **safe space** — all constructive feedback is welcome

---

## ❤️ Part of Our DevEx Vision

This effort is one component of our broader **Developer Experience initiative**, which is focused on:

- Reducing delivery, access, and cognitive friction
- Shortening time to onboarding and flow
- Enabling modern tools, documentation, and support
- Building a world-class environment to **attract and retain top talent**

Thanks for being part of the journey to make our engineering experience the best it can be 🚀
