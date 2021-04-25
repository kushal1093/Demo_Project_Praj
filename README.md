# Demo_Project_Praj

This is the readme file.

Command to copy the project to local machine from github.com:
    git clone <PROJECT_ID>
    eg: git clone https://github.com/kushal1093/Demo_Project_Praj.git

 1. Always create a branch off the "main" branch locally and work on it. The command to create a new branch is:
      git branch -c "foo_branch"

    If you want to get on this branch, do this:
      git checkout "foo_branch"

2. Now make changes that you want to make changes to the project locally by editing the file or creating the new file

3. To view the files that you have modified so far:
     git status

4. To view the "changes" you made to the file(s):
     git diff

5. To "push" all the changes to the remote (or web github repository):
     git add . (this adds all the files that you have made changes to )
     git commit -m "<commit message>"    (eg: git commit -m "Created a dummy python file")


