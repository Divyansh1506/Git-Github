<!-- Commands:  -->

<!-- Git Setup -->

1. git init <br>
Initializes a new Git repository.

2. git clone {URL} <br>
Copies a repository from a specified URL


<!-- Add Files to Repository -->

3. git add {FileName} <br>
Add changes in a file

4. git add . <br>
Add changes in a All file

5. git commit -m "commit message" <br>
Records changes to the repository 

6. git push origin main <br>
Pushes committed changes to a repository

7. git stash <br>
Temporarily saves changes, reverting the working directory to the last commit.
(Ex: Ctrl-x)

8. git stash pop <br>
Applies the most recent stash.
(Ex: Ctrl-v)


<!--  -->

7. git status <br>
Shows the status of changes as untracked, modified, or staged.<br>
Untracked : Not currently being tracked by Git.  <br>
Modified  : Changed in your working directory   <br>
staged    : Marked to be included in the next commit. 


<!-- Branch  -->

8. git branch <br>
Lists all local branches

9. git branch {Name of branch} <br>
Creates a new branch with the specified name.

10. git checkout {Name of branch} <br>
Switches to the specified branch.

11. git checkout -b {Name of branch} <br>
Creates and switches to a new branch.

12. git merge {Name of branch} <br>
Merges the contents of another branch into the current branch.

13. git branch -d {Name of branch} <br>
Delete a branch (if it is not merged).





11. git rm {FileName} <br>
Removes a file from both the working directory and the Git repository.

12. git remote -v <br>
Lists all remote repositories and their URLs

13. git remote add origin {URL} <br>
Adds a new remote repository with a specified name and URL.