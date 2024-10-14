# git-commit-messages.
Good usage practices git commit messages. 

# Message structure.

The message has this structure for identified.

`[{Task Number}] {Change Type}: {Short description}`

**Example**:

` [DOC-002] Doc: Added the information about Message structure `

## Change type:

- feat: A new feature
- fix: A bug fix
- docs: Changes to documentation
- style: Formatting, missing semi colons, etc; no code change
- refactor: Refactoring production code
- test: Adding tests, refactoring test; no production code change
- chore: Updating build tasks, package manager configs, etc; no production code change

# Why I use it?

1. Tracking which activity is related: <br><br>
It is easier and faster to identify which task is related, when the someone of team does the code review, they can easier check if the changes meets task expectations or fix the bug. 

2. The commits tree stay more organizate:<br><br>
The organization of the tree of changes becomes more organized, making it easier to create release notes, as well as having the possibility of automating the release note using the commit messages. 

Add task.


# References
[Udacity Git Commit Message Style Guide](https://udacity.github.io/git-styleguide/)
