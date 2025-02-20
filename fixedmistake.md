# fixed mistakes
* case 1 : staged changes
```
git reset <- file name ->

         or

git reset
```
* case 2 : commited chnages(for one commit)
```
git reset HEAD~1
```
* case 3 : commited changes(for many commits)
```
git reset <- commit hash ->

git reset --hard <- commit hash ->
```
* to show all commits
```
git log
```

