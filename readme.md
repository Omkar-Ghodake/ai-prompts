# AI Prompt Library – Quick Guide

This repository contains **structured AI prompts** for software development work such as building features, debugging issues, testing, maintenance, and upgrades.

The goal is to keep AI usage **clear, controlled, and reusable** without repeating context every time.

---

## Folder Structure
/ai-prompts  
├── development  
├── debugging  
├── testing  
├── maintenance  
├── releases  
└── addons

Each folder represents a **type of work**, not a framework or technology.

---

## How to Use

### 1. Project Start (One Time)

- Use:  
  `development/bootstrapping.md`

- After setup, define project details once using:  
  `addons/project-context.md`

This project context is assumed for all future prompts unless explicitly changed.

---

### 2. Day-to-Day Usage

Choose prompts based on the task:

- Build or modify features → `development/`
- Fix bugs or failures → `debugging/`
- Write or validate tests → `testing/`
- Review or improve existing code → `maintenance/`
- Upgrade dependencies or frameworks → `releases/`

Use **one main prompt per task**.

---

## Add-ons (Optional)

Add-ons modify how the AI behaves and are appended to a main prompt when needed.

Available add-ons:

- `addons/project-context.md` → One-time project definition  
- `addons/confirmation-gate.md` → Ask AI to confirm understanding before coding  
- `addons/git-safety.md` → Safer output for team / shared repositories  

Add-ons are never used alone.

---

## Maintenance Folder Notes

- `maintenance/code-review-audit.md`  
  → Read-only review (no code changes)

- `maintenance/refactor-optimization.md`  
  → Improve code without changing behavior

Choose based on intent.

---

## Basic Rules

- Use one prompt per task
- Add add-ons only when required
- Keep prompts clear and focused
- Prefer confirmation for complex or risky work

---

This system is designed to stay **simple, flexible, and practical**.

