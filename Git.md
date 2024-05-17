### Cloing repos
`git clone https://github.com/<user>/<repo_name>.git`

`cd <repo_name>`

### Making changes
`cd <repo_name>`

`git pull`

`git checkout -b newBranch`

[make the changes]

`git add .`

`git commit -m "Commit message"`

`git push origin newBranch`

[make PR]

`git checkout main`

`git branch -D newBranch`

### Undoing changes that are NOT yet committed
`git reset`

`git checkout .`

`git clean -fd`
