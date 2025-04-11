# My project

## How to remove branches locally and remotely
- **Locally Remove branches:**
  ```bash
  git branch -d branch-name
- **Remotly Remove branches:**
  ```bash
  git push origin --delete branch-name

## Annotated Tags vs Lightweight Tags

- **Annotated Tags:** 
  - Stored as full objects in Git.
  - Includes metadata like tagger name, email, date, and a tagging message.
  - Useful for official releases.

- **Lightweight Tags:** 
  - Just a pointer to a commit.
  - No extra information.
  - More like a branch that doesn't move.
  - 
## When to use Rebase
- Use `rebase` when you want a **clean, linear project history**.
- Especially useful when integrating changes from the main branch into your feature branch.

## How to list tags
- **List tag:**
  ```bash
  git push origin --delete branch-name

## How to delete tag locally and remotely?
- **Locally delete tag:**
  ```bash
  git tag -d tagname
- **Remotly delete tag:**
  ```bash
  git push origin --delete tagname
