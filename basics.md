## Manage Local files
<hr>

- How to check version of Git?
```git
    git --version
```

- How to ignore files in git directory?
```git
    echo "file-name" >> .gitignore
```

- How to check logs in git?
```git
    git log --name-only
    git log --oneline
```

- types of working area in git 
    * working area : area where unsaved changes exist
    * staging area : area where saved changes exist which are ready to be commit
    * committed area : area where commited files exist which are ready to be commited

- basic commands:
    * git add .
    * git commit -m "message"
    * git push origin branch-namer

---
## How to manage Branches?

- How to create new branch and switch to it?
    ```git
    git checkout -b "branch-name"
    ```
- How to create new branch?
    ```git
    git branch "branch-name"
    ```
    
- How to delete branch?
    ```git
    git branch -d "branch-name"
    ```

- How to delete branch?
    ```git
    git branch -d "branch-name"
    ```
- How to list all the branches?
    ```git
    git branch 
    ```
- How to rename a branch?
    ```git
    git checkout "branch name"
    git branch -m "new branch-name"
    ```
- How to push changes to remore repository?
    ```git
    git push orign master
    ```
---

## How to push/Pull changes from remote repository?

- Git Fetch : this command is used to pull changes from remote repository.
```git
    git fetch origin branch-name

```
- Git push : this command is used to push changes to remote repository.
```git
    git push origin branch-name

```
- Git merge : this command is used to merge changes from remote repository to local repository.
```git
    git merge origin branch-name

```
- Git pull : this command is a combination of fetch and merge  command.
```git
    git pull origin branch-name
```

- How to view and check link for remote repository?
```git
    git remote -v

```
- git origin : it is an alias used for remote branch





