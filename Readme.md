# Git Rebase vs Git Merge (Simple Difference)

---

## Git Merge

Git merge combines two branches together and keeps the full history of both branches.

### What happens internally:

- Git takes two branch histories
- Combines them together
- Creates a new **merge commit**
- Keeps original history unchanged

## Git Rebase

Git rebase moves your branch commits on top of another branch.

### What happens internally:

- Git takes your commits
- Temporarily removes them
- Applies them one by one on new base
- Creates a clean linear history
