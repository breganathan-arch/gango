# Contributing

Start with an issue describing the problem, desired result, and how to verify completion. For a bug, include reproduction steps and expected versus actual behavior.

## Making a change

1. Update your local main branch: `git switch main`, then `git pull --ff-only`.
2. Create a branch with a descriptive name, such as `git switch -c improvement/setup-guide`.
3. Make one focused change. Update documentation when behavior or setup changes.
4. Run the project's relevant checks once they are defined. Until code is imported, review documentation and links.
5. Review `git diff` and the staged changes before committing.
6. Push the branch and open a pull request. Describe the result and the checks you ran.
7. If the change completes an issue, include `Closes #NUMBER` in the pull request description, replacing NUMBER with the real issue number.

Never include credentials or private data in issues, screenshots, commits, or pull requests. Use sanitized examples.

Installation and test commands are not yet defined. Add them to the README when the project's language and code are confirmed.
