## Git init  
The Git init command can create a new empty repository in a current directory or re-initialize an existing one.<br>
Syntax : git init

## Git add
Using the Git add command allows Git to track your file and uses the selected file as a parameter when adding it to the staging area. The staging area is a file maintained by Git that contains all the information about what files and changes are going to go into your next commit.<br>
Syntax :<br>
git add .(All files)<br>
git add myFiles.xml(for specefic file)

## Git commit
The .git commit command is run to remove changes made from the staging area to the .git directory. When this command is run, it tells Git to save changes. A text editor is opened that allows a commit message to be entered.<br>
Syntax : git commit -m "commit name"