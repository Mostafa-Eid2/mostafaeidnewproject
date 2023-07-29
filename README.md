

---

## 4- Tell me how to remove them locally and remotely?

Remove Locally:

To remove the 'dev' branch locally:
`git branch -d dev`

To remove the 'test' branch locally:
`git branch -d test`

Remove Remotely:

To remove the 'dev' branch remotely:
`git push origin --delete dev`

To remove the 'test' branch remotely:
`git push origin --delete test`


---


## 5- Tell me how to checkout another branch without commit changes?

If you want to keep your changes temporarily:

`git stash <branch_name>`.

then `git checkout <new-branch-name>`

then `git checkout <old-branch-name>`

Later, use `git stash pop` or `git stash apply` to reapply your changes and keep it in the stash'

---