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


## *Git Workflow*

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


## *Pull Requests and Code Reviews*

### Step 1: Fork a Repository

a. Visited the repository to be contributed to.
b. Clicked the "Fork" button to create a fork in my account.

### Step 2: Create a New Branch and Make Changes

a. Cloned the forked repository to the local machine using `git clone`.
   - 'git clone https://github.com/k3rl15/HelpDesk.git'
b. Navigated to the cloned repository and created a new branch.
   - 'cd "C:\Users\car1b\Projects\HelpDesk"'
   - 'git checkout -b feature-fix-bug'
c. Fixed the dice range bug within the `dice.py` file.
d. Staged and committed the changes.
   - 'git add dice.py'
   - 'git commit -m "Fix the dice range bug"'

### Step 3: Open a Pull Request

a. Pushed the changes to the forked repository.
   - 'git push origin feature-fix-bug'
b. Visited the forked repository on GitHub and created a pull request.

### Step 4: Request Code Review

a. No comments or suggestions were provided.

### Step 5: Address Feedback and Update the Pull Request

e. No updates were necessary.

### Step 6: Merge the Pull Request

a. Once he pull request was approved.
b. Clicked the "Merge Pull Request" button on GitHub.
c. Confirmed the merge.


## *Working with Upstream Repositories*

### Step 1: Find a First Contribution Repository

a. First contributions repository
   - 'https://github.com/firstcontributions/first-contributions'

### Step 2: Fork the Repository

a. Visited the repository's GitHub page.
b. Clicked the "Fork" button to create a fork of the repository in your GitHub account.

### Step 3: Add Upstream Remote and Sync

a. Cloned your forked repository to your local machine:
   - 'git clone https://github.com/k3rl15/first-contributions.git'
b. Navigated to the cloned repository:
   'cd "C:\Users\car1b\Projects\first-contributions"'
c. Added the original repository as an "upstream" remote:
   - 'git remote add upstream https://github.com/firstcontributions/first-contributions.git'

### Step 4: Fetched and merged the latest changes from upstream:
a. Fetched the latest changes from the upstream repository:
   - 'git fetch upstream'
b. Merged these changes into your local repository:
   - 'git merge upstream/main'

### Step 5: Make Additional Changes

a. Made changes to the "Contributors.md" file as required.
b. Checked the status of your changes:
   - 'git status -s'
c. Added the "Contributors.md" file to the staging area:
   - 'git add Contributors.md'
d. Committed your changes with a descriptive message:
   - 'git commit -m "Add Kerlis Gray to Contributors list"'

### Step 6: Push Changes to Your Forked Repository

a. Pushed your local changes to your forked repository:
   - 'git push origin main'

### Step 7: Open a Pull Request

a. Visited your forked repository on GitHub.
b. Clicked on "Contribute," then selected "Open Pull Request."
c. Submitted the pull request.
