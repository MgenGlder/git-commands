### Git Commands I find Useful
Return the symantic ame of the current branch

`git rev-parse --abbrev-ref HEAD`

Access the reflog

`git reflog`

Print the log in one line

`git log --oneline`

Print the log with the patches (the updated code files)

`git log -p`

Show the difference between two commits

`git diff <commit A> <commit B>`

Pop a stash at second index

`git stash pop@{2}`