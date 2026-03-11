# Repository Rules

This document defines the rules and standards for working in the **Team-B repository**.

---

## 1. Folder Naming Convention

All folder names must follow these rules:

• Use **lowercase letters only**
• Do **not use spaces**
• Replace spaces with **hyphen (-)**
• Use clear and meaningful names

Examples:

Correct:

* jio-black-rock
* bajaj-electricals
* gharda-chemicals
* life-after-law

Incorrect:

* Jio Black Rock
* Bajaj Electricals
* gharda chemicals
* LifeAfterLaw

---

## 2. Developer Workspace Rules

Each developer has their own folder inside:

developers/

Example:
developers/rohit/

Rules:

• Developers may **only add files inside their own folder**
• Do **not modify other developer folders**
• Use Pull Requests for any shared changes

---

## 3. Project Folder Rules

All client projects are stored inside:

projects/

Example:
projects/bajaj-electricals/

Rules:

• Project folders must follow the naming convention
• Changes to project folders must go through **Pull Requests**
• Direct commits to project folders should be avoided

---

## 4. Git Workflow

All development must follow the Pull Request workflow.

Steps:

1. Create a branch
2. Make changes
3. Push branch
4. Create Pull Request
5. Review & merge

Example branch:

feature/rohit-update

---

## 5. Restricted Actions

The following actions are **not allowed**:

• Editing another developer's folder
• Direct push to `main` branch
• Creating folders with spaces or uppercase letters
• Deleting project folders without approval

---

## 6. Best Practices

• Keep commits small and meaningful
• Write clear commit messages
• Document important changes
• Maintain folder organization

---

## 7. Repository Structure

Team-B
│
├── developers/
├── projects/
├── docs/
├── .github/
└── README.md

---

Following these rules helps maintain a clean and scalable repository structure.
