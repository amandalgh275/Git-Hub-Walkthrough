Summary
This PR adds about.txt which documents how to add files to Git (using git add and git status). It's intended as a small, beginner-friendly explanation for the repository.

Changes
- Add file: about.txt
  - Describes using `git add .` and `git add about.txt`
  - Explains the staged state and using `git status` to check file state

Why this change
- Provides a short reference for new contributors learning how to stage files and check their status before committing.
- Improves repository documentation and onboarding.

How to review
1. Open about.txt in the repository tree and confirm the text accurately and clearly explains:
   - the difference between `git add .` and `git add <file>`
   - that `git add` stages changes
   - using `git status` to view staged files
2. Check for typos, wording clarity, and formatting.
3. Optionally, verify the file renders correctly on GitHub.

Testing / verification
- No code changes; manual review of the file content is sufficient.

Notes
- This is a documentation-only change and should be safe to merge without additional CI.
- If you prefer different wording or want the file moved to a docs/ folder, let me know and I can update.

Suggested reviewers
- (add one or two teammates here)

Suggested labels
- documentation
- good first issue (optional)
