# GitHub Support

A Git & GitHub guide for students, built for TA office hours support. Covers git basics, branching & merging, and the GitHub collaboration workflow (forks, pull requests, code review, issues, and a light intro to Actions), plus a troubleshooting cheat sheet for common errors.

**Live site:** https://ganowacek.github.io/github-support/

## Contents

- [Git Basics](git-basics.html) — install/config, the three areas, core commands, `.gitignore`, undoing changes, remotes
- [Branching & Merging](branching-merging.html) — creating branches, merging, resolving conflicts, rebasing
- [GitHub Workflow](github-workflow.html) — forking vs. cloning, pull requests, code review, issues, GitHub Actions, troubleshooting

## Editing locally

This is a plain static site — no build step. Open `index.html` directly in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
