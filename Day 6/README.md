# Git Assignment README

## *Branching Strategies*

### Step 1: Initializing the Repository

a. Created a new folder named "Git Assignments."
b. Navigated to the folder path in the command prompt.
c. Executed 'git init' to initialize a new Git repository.

### Step 2: Creating Feature Branches

a. Created two feature branches using the 'git checkout -b' command:
   - "feature-login"
   - "feature-logout"

### Step 3: Implementing Features

a. Switched to the "feature-login" branch using 'git checkout feature-login'
b. Executed 'echo TODO > login.py' to create a placeholder file for the login feature.
c. Added the "login.py" file to the staging area with 'git add login.py'
d. Switched to the "feature-logout" branch using 'git checkout feature-logout'
e. Executed 'echo TODO > logout.py' to create a placeholder file for the logout feature.
f. Added the "logout.py" file to the staging area with 'git add logout.py'

### Step 4: Committing Changes

a. While on the "feature-login" branch, committed the changes with 'git commit -m "Implement login feature."'
b. On the "feature-logout" branch, committed the changes with 'git commit -m "Implement logout feature."'

### Step 5: Pushing to a Remote Repository

a. Set up a link to the remote repository with 'git remote add main https://github.com/k3rl15/skill_captain_git.'
b. Pushed the "feature-login" branch to the remote repository with 'git push main feature-login.'
c. Pushed the "feature-logout" branch to the remote repository with 'git push main feature-logout.'


## *Git Workflow README*

This repository demonstrates a simple Git workflow with the following steps:

### Step 1: Create and Switch to "develop" Branch

a. Switch to the "main" branch using 'git checkout main.'
b. Create a new branch named "develop" using 'git checkout -b develop.'

### Step 2: Implement Additional Changes

a. While on the "develop" branch, execute the following commands:
   - 'echo TODO > develop.txt' to create a file for additional changes.
   - 'git add develop.txt' to stage the file.
   - 'git commit -m "Additional changes related to login and logout feature"' to commit the changes.

### Step 3: Push Changes to Remote Repository

a. Push the "develop" branch to the remote repository:
   - 'git push main develop.'

### Step 4: Merge "develop" Branch into "main"

a. Switch back to the "main" branch using 'git checkout main.'
b. Merge the changes from the "develop" branch into the "main" branch using 'git merge develop.'

