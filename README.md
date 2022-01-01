# Get your Git correctly! :sunglasses:

![alt text](https://github.com/vidush5/Git-Learning/blob/main/git.png)

Git is the most popular distributed version control system. Git was developed by Linus torvalds.

I will list down most essential git commands which everyone should master when handling github repositories.

## Git Commands

01. Set up your reposirory details (username and email).

```
    git config --global user.name "vidush5"
```

```
    git config --global user.email "vidushraj5@gmail.com"
```

02. Cache your login details.

```
    git config --global credential.helper cache
```

03. Initialize a github repository.

This folder contains all the objects and references that git uses and it creates as a part of your projects's history.


```
    git init
```

04. Add single file to staging area.

```
    git add helloworld.py
```

05. Add multiple files to staging area.

```
    git add .
```

06. Check your repository status.

```
    git status
```

07. Commit your changes in your repository.

```
    git commit -m "my first commit"
```

08. To check commit history with changes.

```
    git log -p
```

09. To view the changes before commiting.

```
    git diff
```

10. To see the staged changes.

```
    git diff --staged
```

11. Remove files

```
    git rm helloworld.py
```

12. Rollback last commit
you can rollback the last commit and it will create a new commit, an inverse of the previous commit.

```
    git revert HEAD
```

13. Rollback a particular commit.

```
    git revert <commit id>
```

14. Create a new branch.

```
    git branch <branch_name>
```

15. Switch to the branch.

```
    git checkout <branch_name>
```

16. List down all branches.

```
    git branch
```

list down all remote branches.

```
    git branch -a
```

17. Delete a branch.

```
    git branch -d <branch_name>
```

To delete forcible a branch.

```
    git branch -D <branch_name>
```

The above commands only delete the local copy of the branch, if you want to delete a remote branch follow the below command.

```
    git push origin --delete <branch_name>
```

18. Merge two branches.

```
    git merge <branch_name>
```

Merge with commit.

```
    git merge --no-ff <branch_name>
```

19. Push changes to a remote repository.

```
    git push origin main 
```

20. Pull changes from a remote repository.

```
    git pull
```







   



