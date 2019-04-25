# git-utils
List of git commands used all daylong.

## Basic commands
```
$ git config [-global] [-l] user.name "user.name"
$ git init <repo.name>
$ git clone "url"
$ git add .
$ git commit [-S] -m "message"
$ git diff [-staged] [first.branch] [last.branch]
$ git status
$ git fetch
$ git pull
$ git push [--force]
$ git log [--oneline]
$ git branch [-d] <branch.name>
$ git checkout [-n] <branch.name>
$ git merge <branch.name>
```

## Intermediate commands
```
$ git reset <commit>
$ git tag <commit>
$ git stash [save/list/pop/drop]
```

## Remove file commit histories 
```
$ git filter-branch --index-filter 'git rm --cached --ignore-unmatch path/file' <initial.commit>..<final.commit>/HEAD
$ git push --force
```

## References
A nice [Git Cheat Sheet](https://github.com/hbons/git-cheat-sheet) from hbons, see it! :D  
More info at [Git](https://git-scm.com/) website and [Git documentation](https://git-scm.com/doc).
