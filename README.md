Learn to Git

### Getting & Creating Projects
```bash
git init 2222

git clone <git-url>
```

### Updating Your Project
```bash
git remote -v

git remote add <repo-name> <git-url>

git remote set-url <repo-name> <git-url>

git remote remove <repo-name>

git checkout <filename> # use dot(.) to checkout the whole folder

git checkout <branch-name> # Switch to branch 'branch-name'

git checkout -b <branch-name> # Creat a new branch 'branch-name' and switch to it

git status

git add <filename> # use dot(.) to add the whole folder

git commit -m "commit message goes here"

git reset HEAD <file-name>
```

### Branching & Merging
```bash
git branch

git branch -a

git branch <branch-name>

git branch -d <branch-name> # delete branch branch-name

git merge <source-branch> # merge source-branch to active branch

git merge <source-branch> <target-branch> # merge source-branch into target-branch
```

### Sharing & Updating Projects
```bash
git pull

git push

git pull <repo-name> <branch-name> # git pull origin  master

git push <repo-name> <branch-name> # git push origin  master
```

### Playing with Remote Branches
```bash
git push origin --delete <remote-branch-name> 
```

### Advanced
```bash
git reset --hard <commit-id> # only run there are no uncommited changes

git revert 
```

### Inspection & Comparison
```bash
git log

git diff

git diff <branch-1> <branch-2>
```
