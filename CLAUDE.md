# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is a teaching repository for a 45–60 minute Git/GitHub workshop. It has no build system, test suite, or application code. All meaningful content lives in `README.md`, which is the lesson plan and the artifact students interact with during the demo.

## Repository conventions

- `README.md` is the primary deliverable — it doubles as the workshop lesson plan and the live demo document students clone and work with.
- Branch names used in the workshop follow the pattern `feature/<short-description>` (e.g., `feature/add-intro-section`).
- Commits during the demo are intentionally small and illustrative; commit messages are written for pedagogical clarity, not production hygiene.

## Workshop flow

The lesson progresses through these stages (detailed in README.md):

1. Setup & orientation — confirm Git is installed, configure identity
2. Clone the repo — students clone this repo from GitHub
3. Branching — create a feature branch
4. Edit → Stage → Commit loop — make a small change, stage it, write a message
5. Push & pull — push the branch, open a pull request
6. Merge — merge PR into main on GitHub, pull changes locally
7. GUI demos — repeat key steps in VS Code Source Control panel and RStudio Git pane

## Working in this repo

There are no build, lint, or test commands. The only relevant Git operations are standard workflows demonstrated in the lesson. If you add scripts or code samples as workshop exercises, note them here.
