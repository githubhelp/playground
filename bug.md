### Question Regarding Pull Requests

1. `petros` creates `test-bug` off of `master` in `githubhelp/playground`
2. Adds a file named `bug.md` with some content and creates a commit
3. Publishes and syncs the new branch
3. Creates a pull request (#30) from within GitHub Desktop
5. Clicks on #30 and the pull request opens up in the web browser
6. `petros` comments and closes the pull request and returns to GitHub Desktop
7. Clicks on #30 and the pull request opens up in the web browser (expected)
8. Adds a new commit (by changing something in `bug.md`)
9. Syncs
10. Clicks on where #30 was showing up before to create a new pull request (expected)

*This behavior is expected*
