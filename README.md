# GitHub Automation Lab – Daily Heartbeat & DevOps Workflows

This repository is my personal lab for experimenting with **GitHub Actions**, automation, and DevOps workflows.

It showcases:
- ⏰ Scheduled workflows (daily heartbeat commits)
- ✅ Basic CI pipelines
- 🧹 Automated linting using GitHub Super Linter
- 🧪 A playground for future CI/CD and DevOps experiments

---

## 🔥 Daily Heartbeat Workflow

The repo contains a workflow that runs **every day at 2:00 AM IST (Asia/Kolkata)**.

What it does:

- Updates a file called `heartbeat.md` with the current IST timestamp.
- Creates a commit with a clean, professional message:
  - `chore: daily heartbeat update - YYYY-MM-DD`
- Ensures daily activity on the repository and demonstrates:
  - GitHub Actions
  - Cron-based scheduling
  - Automation with bash scripting

You can find this workflow here:

```text
.github/workflows/daily-heartbeat.yml
