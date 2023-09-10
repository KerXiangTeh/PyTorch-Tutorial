# ToastyAI will save the world.
# PyTorch-Tutorial
This repository contains ToastyAI's inaugural PyTorch project, publicly available.

Checking git command install:
1. Install [git cli](https://git-scm.com/downloads)
2. Run `git clone <repo_URL>`
    For this one `git clone https://github.com/KerXiangTeh/PyTorch-Tutorial.git`
3. `cd` to the proper directory, `PyTorch-Tutorial`
4. Run the GitSmart.py script to make sure it runs

Using git to create a branch:
After you clone, good practice is to create a branch to start working on the changes you want to make 
1. Run `git checkout -b <branch_name>`
    Name can't have spaces; instead, use dashes `-`
2. Make the changes/updates/additions you want

Using git to save and push update:
After you've done the changes you want, you'll want to save the changes and 
push the changes to the remote repository for others to pull.
Staging the change
1. `git add path/file1, path/file2, path....`
    Optionally, if you're using VSCode, you can use the GUI to stage the changes
        by using the Source Control panel on the left
    Or you can use `git add .` - bad practice. Might add changes you didn't intend 
Commiting the change
1. `git commit -m "put what this change in the code will do"`
Pushing the change
1. `git push`
    This will push your local commits into a merge request on Github for others to review before merging into the main branch 