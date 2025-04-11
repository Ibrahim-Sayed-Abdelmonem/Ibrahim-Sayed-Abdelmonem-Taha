# My project
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

