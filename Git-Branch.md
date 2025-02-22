## Git Branch

[Git Branch](https://git-scm.com/docs/git-branch) is a pointer to a specific commit in git. It allows teams of developers to easily collaborate inside of one central code base. When a developer creates a branch, the version control system creates a copy of the code base at that point in time. Changes to the branch don't affect other developers on the team.

To check which branch your currently in, you can use the command ```git branch``` It will then display the list of the available branches. The one with the ```*``` at the beginning is the your currently in.

## Creating a branch

to create a branch, we can use the command:
```
git branch <NAME OF THE BRANCH>
```
<br>

Alternatively, if you want to create a branch and immediately go to that created branch, we can use the command:
```
git checkout -b <NAME OF THE BRANCH>
```
<br>




