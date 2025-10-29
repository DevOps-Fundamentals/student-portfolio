# **Student Portfolio Showcase – DevOps Assignment 01 (Fall 2025)**

Welcome to the Student Portfolio Showcase repository. A collaborative project developed as part of DevOps Fundamentals Fall 2025.

This project demonstrates our team’s understanding of Git workflow, branching strategies, pull requests, rebasing, and release management using GitHub in a real-world setup.

## **Project Overview**

The Student Portfolio Showcase is a multi-page website designed to highlight students’ profiles, projects, skills, and achievements.
It includes five interlinked HTML pages, all styled with a shared responsive CSS file.

## **Folder Structure**

student-portfolio/

│

├── .gitignore

├── README.md

└── src/

    └── index.html

    └── profile.html

    └── projects.html

    └── skills.html

    └── achievements.html

    └── about.html

└── styles/
    └── style.css

Each page is collaboratively developed on separate feature branches and integrated through protected pull requests for a clean, linear Git history.

## **Team Roles & Responsibilities**
| **Role**             | **Name**                     |           **Responsibilities**                                                                                        |
| ------------------------- | ------------------------------- | ---------------------------------------------------------------------- |
| **Team Lead** | Muhammad Ahmad | Repository setup, baseline commits, branch protection, issue management, release creation, final merges |
| **Member 1**  | Yasir Iftikhar | Develops `profile.html`                                                                                 |
| **Member 2**  | Muhammad Rayyan | Develops `projects.html`                                                                                |
| **Member 3**  | Abdul Wahab Subhani | Develops `skills.html`                                                                                  |
| **Member 4**  | Kaif Baig | Develops `achievements.html`                                                                            |
| **Member 5**  | Umar Daraz | Develops `about.html` | 

## **Git & GitHub Workflow**

**1. Main Branches:** `main` (production) and `develop` (integration)

**2. Feature Branches:** `feature/<page-name>` for individual work

**3. Branch Protection:**
    1. No direct pushes
    2. PR required with 2 approvals for `develop`
    3. 3 approvals for `main` merges

**4. Rebase & Merge:** All PRs rebased before merge to maintain clean history

## **Features**

1. Responsive and modern design using CSS media queries

2. Clear navigation across all pages

3. Centralized styling via styles/style.css

4. Clean Git workflow reflecting DevOps best practices

## **Team Summary**

This project strengthened our teamwork, communication, and Git collaboration skills.
We faced minor merge conflicts in the shared CSS file, which were resolved collaboratively through pull request reviews and rebasing.

## **Repository URL**

**GitHub Repository:** [Student Portfolio](https://github.com/DevOps-Fundamentals/student-portfolio.git)