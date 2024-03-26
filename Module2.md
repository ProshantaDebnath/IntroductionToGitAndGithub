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

## Creating new branch
git branch proshanta

## Switching new branch
git checkout master

## creating and switching a new branch shortcut
git checkout -b branchProshanta

## Deleting branch
git branch -d branchProshanta

## Merging branch
git merge proshanta

## Notes :-

Branch: A pointer to a particular commit, representing an independent line of development in a project<br>

Commit ID: An identifier next to the word commit in the log<br>

Fast-forward merge: A merge when all the commits in the checked out branch are also in the branch that's being merged<br>

Head: This points to the top of the branch that is being used<br>

Master: The default branch that Git creates for when a new repository initialized, commonly used to place the approved pieces of a project<br>

Merge conflict: This occurs when the changes are made on the same part of the same file, and Git won't know how to merge those changes<br>

Rollback: The act of reverting changes made to software to a previous state <br>

Three-way merge: A merge when the snapshots at the two branch tips with the most recent common ancestor, the commit before the divergence<br>



