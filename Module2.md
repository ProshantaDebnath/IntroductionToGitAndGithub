## .gitignore files
.gitignore files are used to tell the git tool to intentionally ignore some files in a given Git repository. For example, this can be useful for configuration files or metadata files that a user may not want to check into the master branch.<br>
[.gitignore](https://git-scm.com/docs/gitignore)<br>
[.gitigonre file sturcture](https://gist.github.com/octocat/9257657)

## Undoing changes in staging area
(use "git reset HEAD <file>..." to unstage)<br>
new file:   output.txt<br>
Syntax :<br>
git reset HEAD output.txt


## Git Checkout
Git checkout is used to creat new branch/ switching one brach to another<br>
Syntax : <br>
git checkout -b proshanta(for creating new branch)<br>
git checkout master(for switching to new branch)

## Single line cmd to direct commit
Syntax:<br>
git commit -a -m "Commit message"

## Git Revert 
The git revert command is used for undoing changes to a repository's commit history.
Syntax:<br>
git revert Head<br>
[Git Revert](https://git-scm.com/docs/git-revert)<br>
Seeing the last two commit in the log : git log -p -2

## Git log
The git log command displays committed snapshots
Syntax:<br>
git log<br>
git log -2 (it shows the last two commit)

## Git Show
The git show command is used to view the changes of a specific commit.
Syntax : <br>
Example: commit id--->01jhhkah3ooh52<br>
git show 01jhhkah3ooh52

