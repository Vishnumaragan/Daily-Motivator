# Daily-Motivator

## Introduction
Daily-Motivator is a frontend web application built with HTML, CSS, and JavaScript. The project was developed to demonstrate practical use of Git Bash and GitHub for a Version Control Systems course. It provides a daily motivational quote generator alongside simple utility pages including a to‑do list, login/signup UI, and a feedback page.

## Project Objectives
- Demonstrate branch-based feature development and merging workflows in Git.
- Provide a clear, functional frontend demo that highlights basic UI features: quotes, task management, authentication UI, and feedback.
- Produce a concise repository history suitable for academic evaluation (feature branches, merge commits, and conflict resolution).

## Technologies Used
- HTML
- CSS
- JavaScript
- Git / GitHub (version control and branching)

## Folder Structure
The repository structure is shown exactly as implemented:
<img width="276" height="537" alt="image" src="https://github.com/user-attachments/assets/148822cf-89a2-4d27-b16b-9116f9952b22" />


## Branches Used
- `main`
- `Quote`
- `feedback`
- `login-signup`
- `to-do`

Each feature was developed in its own branch and later merged into `main`.

## Merging Process
- Development workflow: create a branch per feature (e.g., `Quote`, `to-do`, `login-signup`, `feedback`), implement and commit feature changes, push the branch, open a pull request, and merge into `main`.
- All feature branches were merged into `main` following review and basic testing.
- Merge commits were created at each merge point (reflecting branch merges into `main`).

## Merge Conflict & Resolution
- A merge conflict occurred while merging the `feedback` branch into `main`.
- The conflict was resolved by editing the affected files to reconcile changes, staging the resolved files, and committing the result.
- Conflict resolution commit message used:
  - `fixed errors caused by merge with feedback`

## Commit History Expectations
- Initial project setup commit (project scaffold and base files).
- Feature-based commits (focused changes per feature branch).
- Multiple merge commits from the feature branches into `main`.
- At least one post-merge bug fix commit addressing issues introduced by merging (see the conflict resolution commit above).


## Challenges Faced
- Balancing concise commit granularity suitable for academic grading while keeping the history readable.

## Learning Outcomes
- Applied branch-per-feature workflow and practiced creating, reviewing, and merging branches.
- Experienced real-world merge conflict resolution and learned to produce clear, descriptive commit messages for fixes.
- Reinforced fundamentals of frontend development with modular files for features and UI components.
- Gained practical experience using Git Bash and GitHub as required for the Version Control Systems course.

## Conclusion
Daily-Motivator is a compact, course-oriented frontend project illustrating disciplined Git workflows: isolated feature branches, merging into `main`, handling merge conflicts, and producing a clear commit history for academic evaluation. The project structure and commit practices are designed to be reproducible and educational.

## GitHub Repository Link
repository URL :
https://github.com/Vishnumaragan/Daily-Motivator

