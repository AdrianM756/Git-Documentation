
## Git Reset

[git reset](https://git-scm.com/docs/git-reset) allows you to undo the changes in your working directory and get back to a specific commit while discarding all the commits made after that one. For example, let's say that you made ten commits. Using git reset on the first commit will remove all nine commits, taking you back to the first commit stage. To do this, we can use the command:
```
git reset <COMMIT HASH/COMMIT I.D.>
```
<br>

To look for the commmit hash/I.D., we can use the command:
```
git log
```
<br>

Alternatively, for a more brief information, we can use the command:
```
git log --oneline
```
<br>

## Git Revert

[git revert](https://git-scm.com/docs/git-revert) allows you to record some new commits to reverse the effect of some earlier commits (often only a faulty one). Git revert is quite similar to git reset, but the approach is slightly different. Instead of removing all the commits in its way, the revert ONLY undoes a single commit by taking you back to the staged files before the commit. To do this, we can use the command:
```
git revert <COMMIT HASH/COMMIT I.D.>
```
<br>



