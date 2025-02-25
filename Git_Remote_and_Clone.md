## Git Remote

[git remote](https://git-scm.com/docs/git-remote) Allow your to manage your set of tracked repositories.

To add a git remote repository on your system, We can use the command:
```
git remote add origin <REMOTE REPOSITORY LINK>
```
<br>

***Explaination:***

```git add``` can be used to add a branch, master, or a repository.

```origin``` is an alias that refers to the remote repository URL. By convention, "origin" is used for the primary remote repository, but you can use any name you prefer.

```<REMOTE REPOSITORY LINK``` refers to the git repository link.
<br>

To check the list of all the available remote repository, we can use the command:
```
git remote -v
```
<br>

If for instance, you want to change the URL of your remote repository but you don't want to change the namem we can use the command:
```
git remote set-url origin <NEW REPOSITORY LINK>
```
<br>

Once done, you can now pull and push to your remote repository.
<br>
<br>

## Git Clone

[git clone](https://git-scm.com/docs/git-clone) allows you to copy of an existing repository into a new repository either from a local or remote repository. We can use this using the command:
```
git clone <REPOSITORY LINK THAT YOU WANT TO COPY>
```
<br>


