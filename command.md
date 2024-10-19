# Git for DevOps Commands

1. **Create a directory**:
   Command: mkdir git-for-devops
   Description: Creates a new directory called 'git-for-devops'.

2. **List contents of the directory**:
   Command: ls git-for-devops/
   Description: Lists all files and subdirectories within 'git-for-devops'.

3. **Check current directory path**:
   Command: pwd
   Description: Displays the present working directory.

4. **Change to the directory**:
   Command: cd git-for-devops/
   Description: Moves into the 'git-for-devops' directory.

5. **Initialize a Git repository**:
   Command: git init
   Description: Initializes a new Git repository in the current directory.

6. **List all files including hidden**:
   Command: ls -a
   Description: Lists all files in the directory, including hidden files.

7. **Create a new file (hello.txt)**:
   Command: vim hello.txt
   Description: Opens 'hello.txt' in the Vim text editor, or creates it if it doesn’t exist.

8. **Check the status of the repository**:
   Command: git status
   Description: Shows the current state of the working directory and staging area.

9. **Create new files (1, 2)**:
   Command: touch 1 2
   Description: Creates two new empty files named '1' and '2'.

10. **Stage specific files for commit**:
    Command: git add 1 2 hello.txt
    Description: Adds the files '1', '2', and 'hello.txt' to the staging area.

11. **Stage all files for commit**:
    Command: git add .
    Description: Stages all modified and newly created files for the next commit.

12. **Commit changes with a message**:
    Command: git commit -m "adding nibba nibbi"
    Description: Records changes to the repository with the message "adding nibba nibbi".

13. **Set global email configuration**:
    Command: git config --global user.email "saumil1201@gmail.com"
    Description: Sets the global email for commits made by the user.

14. **Set global username configuration**:
    Command: git config --global user.name "saumil1201"
    Description: Sets the global username for commits made by the user.

15. **Modify file (1)**:
    Command: vim 1
    Description: Opens or creates file '1' in the Vim text editor.

16. **Add modified file (1)**:
    Command: git add 1
    Description: Stages the modified file '1' for the next commit.

17. **Commit modified file**:
    Command: git commit -m "add modified 1 number file"
    Description: Records the changes to the modified file '1' with the message.

18. **Remove a file (1)**:
    Command: rm -r 1
    Description: Deletes the file or directory '1'.

19. **Restore deleted file**:
    Command: git restore 1
    Description: Restores the file '1' from the last commit.

20. **Create a new branch (dev)**:
    Command: git checkout -b dev
    Description: Creates a new branch called 'dev' and switches to it.

21. **Switch to master branch**:
    Command: git checkout master
    Description: Switches to the master branch.

22. **Switch back to dev branch**:
    Command: git checkout dev
    Description: Switches back to the 'dev' branch.

23. **Create a new file (nibbu.txt)**:
    Command: touch nibbu.txt
    Description: Creates a new empty file called 'nibbu.txt'.

24. **Stage and commit the new file**:
    Command: git add nibbu.txt
    Command: git commit -m "added nibbu"
    Description: Stages and commits the file 'nibbu.txt' with the message "added nibbu".

25. **View commit log**:
    Command: git log
    Description: Displays the commit history.

26. **View short log**:
    Command: git log --oneline
    Description: Displays a simplified commit history with one commit per line.

27. **Switch to superuser (optional)**:
    Command: sudo su
    Description: Switches to the superuser (root).

28. **View command history**:
    Command: history
    Description: Displays the list of previously executed commands.

29. **List directory contents**:
    Command: ls
    Description: Lists all files and directories in the current directory.
