# 🧮 Project Euler — Solutions Archive

A structured, fully automated archive containing problem descriptions and verified solutions for **1,000 Project Euler problems**. 

---

## 📌 Project Overview

[Project Euler](https://projecteuler.net) is a series of challenging mathematical/computer programming problems designed for people interested in exploring mathematics and coding. 

This repository serves as a personal archive of solved problems, automatically partitioned into individual directories to ensure clean categorization and easy navigation.

---

## 🗂️ Repository Structure

Every problem is structured inside its own dedicated directory:

```text
Project Euler/
│
├── 📁 Problem 001 - Multiples of 3 and 5/
│   ├── 📄 problem.md        # Full description & link to official site
│   └── 📄 solution.md       # Verified numerical answer
│
├── 📁 Problem 002 - Even Fibonacci numbers/
│   ├── 📄 problem.md
│   └── 📄 solution.md
│
├── 📁 Problem 003 - Largest prime factor/
│   ├── 📄 problem.md
│   └── 📄 solution.md
│
│   ... (Problems 004 to 994) ...
│
├── 📁 Problem 995/           # Unnamed placeholder (not yet published)
│   ├── 📄 problem.md
│   └── 📄 solution.md
│
│   ... (up to Problem 1000) ...
│
└── 📄 Solutions.md           # Master list of all 1,000 answers
```

### 🏷️ Folder Naming Conventions
* **`Problem <ID> - <Title>`**: Sourced from official archives (available for problems 1 to 994).
* **`Problem <ID>`**: Retained for unpublished or unnamed problems (problems 995 to 1000).

---

## 📄 File Templates

Each problem folder contains two main files:

### 1. `problem.md` (Problem Description)
Includes the formatted problem statement along with a reference link to the official problem.
```markdown
# Problem 001 - Multiples of 3 and 5

## Description
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

---
[Link to problem on Project Euler](https://projecteuler.net/problem=1)
```

### 2. `solution.md` (Numerical Answer)
Contains the verified final solution.
```markdown
# Problem 1 Solution

The solution to Project Euler Problem 1 is:

**233168**
```

---

## 📊 Archive Statistics

| Metric | Details |
| :--- | :--- |
| **Total Solutions** | `1,000` (parsed from `Solutions.md`) |
| **Fully Documented Descriptions** | `918` (problems 1–918) |
| **Official Titles Named** | `994` (problems 1–994) |
| **Placeholders (Unreleased)** | `6` (problems 995–1000) |
| **Latest Published Problem** | *Problem 994: Counting Triangles* |

---

## 🛠️ Extraction Details
To bypass Project Euler's strict rate limits (which cause immediate `403 Forbidden` / `502 Bad Gateway` blocks on scrapers), the repository structure was built using a multi-step extraction method:
* **Solutions** parsed directly from the local master file `Solutions.md`.
* **Descriptions** for problems 1–918 pulled from the community Hugging Face dataset `alexandonian/project-euler`.
* **Titles** for problems 919–994 scraped programmatically using automated browser sessions.

---

> ⚠️ **Disclaimer**: The answers stored in this archive are for educational purposes and personal reference. To get the most out of Project Euler, try to solve each problem on your own before consulting the solutions.

---

## ✍️ Signature

Created and maintained by **[Ahmed Fawzy](https://github.com/ahmedfawzyjr)**.
