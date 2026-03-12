# Introduction to Git

## This repository

This repository is meant to be the git repo as used in a introductory training to git.

In order to use this;
1. Fork it
2. Allow people to clone _the fork_
3. People can then work on the assignments



## Assignments

### 0a. Preparation for local development
0. Create a [Github account](github.com)
1. Install the required programs:
  * [git](https://git-scm.com/install/)
  * Install [Python](https://www.python.org/downloads/)
  * Install [Visual Studio Code](https://code.visualstudio.com/download)
2. Configure git to use your github account credentials
3. Install the python dependencies: in a terminal type: `pip install uv`
4. Clone the repository locally using the `git clone` command in your terminal

### 0b Preparation for codespace development
0. Create a [Github account](github.com)
1. Go to this repository
2. Open a codespace on the `master` branch

### 1. Git Basics
0. Run the FastAPI application using `uv run fastapi dev` (make sure your terminal is in the `/src/` folder).
1. Create a new route in the `app.py` file, and sync your changes
   After this, commit and push your changes to the master branch
2. Pull changes from the remote
3. Add an image file and an endpoint from which you can get the image file. Then commit and push your changes to the remote (multiple files!). 
4. Create a new file and fill it with random stuff, and delete your `app.py` file. Then undo your changes using `git reset`.
5. Create a file called `secrets.txt` and fill it with secrets you do not want to leak to the outside world.
   Then add the file to the `.gitignore` file.

### 2. Advanced Git
1. Create a new branch and work on it, using either `git branch` or `git checkout -b`
2. Merge your new branch locally using `git merge`
3. Let's create and solve a merge conflict!
4. Create a new branch and let's create your first pull request!
5. Let's make a new mistake, push it to the remote and undo it using `git revert`




