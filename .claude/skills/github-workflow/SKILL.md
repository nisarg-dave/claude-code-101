---
name: github-workflow
description: Commit changes to Git and push to remote repository. Use after completing meaningful work that needs to be saved.
---

# GitHub Workflow

## Commit & Push

After completing meaningful work:
1. Run `git status` and `git diff` to review changes
2. Run `git log` to see recent commit message style
3. Stage specific files (avoid `git add -A`)
4. Create commit with descriptive message ending with:
   ```
   Co-Authored-By: minimax-m2.7 <noreply@anthropic.com>
   Or: Co-Authored-By: Claude Opus 4.6 <noreply@anthropic.com>
   ```
5. Push to GitHub

## Commit Message Guidelines
- Focus on the "why" not the "what"
- Keep it concise (1-2 sentences)
- Use present tense ("Add feature" not "Added feature")