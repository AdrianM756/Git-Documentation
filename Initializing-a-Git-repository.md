## Initializing a repository

To create an empty Git repository or reinitialize an existing repository, we can use the command:
```
git init
```
<br>

Once ```git init``` is executed, it will then create a file called ```.git```. The ```.git``` folder contains all the information that is necessary for your project in version control and all the information about commits, remote repository address, etc.

## Working Tree

When we create or modify a file in the git repository, it stays in the [working tree or working area](https://medium.com/@lucasmaurer/git-gud-the-working-tree-staging-area-and-local-repo-a1f0f4822018). It is the area where you are currently working. It is where your files live. This area is also known as the “untracked” area of git.

## Staging Tree

The [staging tree or staging area](https://medium.com/@lucasmaurer/git-gud-the-working-tree-staging-area-and-local-repo-a1f0f4822018) is when git starts tracking and saving changes that occur in files. These saved changes reflect in the ```.git``` directory.

## Git Status

Git status shows you the list of what is in you Working Tree and Staging Area. To check the changes that are made in the git repository, we can use the command:
```
git status
```
<br>

## Git Add

Git add allow you the track and add a file in a staging area. To do this, we can use the command:
```
git add <FILENAME YOU WANT GIT TO TRACK>
```
<br>

Additionally, if we want to track all the files insider the repository, we can achieve that using the command:
```
git add --all
```
<br>

If we want to remove a file from being tracked, we can use the command:
```
git rm --cached <FILENAME YOU WANT TO UNTRACK>
```
<br>

## Git User and Git Commit

To commit a file, we can use the command:
```
git commit -m "<MESSAGE>"
```
<br>

But before we perform a commit, Let us first configure the a git user in which we will set a the git username and user email. To do that, we will use the command:
```
git --global config user.name "<YOUR USERNAME>"
git --global config user.email "<YOUR USER EMAIL>"
```
<br>

***Questions:***

* Can I still perform a commit without configuring a git user?

***Explaination:***

Yes you can still perform a commit without setting up a git user. **However**, it is recommended to set it up as it is used to identify the author of the commits.
<br>
<br>

## Git Ignore

A ```gitignore``` file specifies intentionally untracked files that Git should ignore. To add a file to a ```gitignore``` file, we can use the command:
```
echo NAME_OF_FILE >> .gitignore
```
<br>

Then when you run the ```git status``` command, the file will not appear at all.


