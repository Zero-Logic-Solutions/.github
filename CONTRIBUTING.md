# How We Build Apps

This doc outlines our engineering team's standard process for shipping code.

## 1. Branching

-   All work happens on a feature branch.
-   Branch names must include the feature: `feature/short-description`.
-   Never commit directly to `main`.

## 2. Commits

-   Commit messages should be clear and descriptive.
-   Reference the feature in your commit messages if possible.

## 3. Pull Requests (PRs)

1.  **Create a Draft PR** early to show work-in-progress.
2.  **Fill out the PR template** completely. This is not optional.
3.  **Request a review** from at least one other team member.
4.  **Merge using "Squash and Merge"** once approved and all checks pass. This keeps our `main` branch history clean.
