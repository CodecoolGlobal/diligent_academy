## GIT and GitHub

**Required Tools:**
* Computer (Windows, Linux, or macOS)
* Internet connection
* Text editor or IDE (e.g., Visual Studio Code)
* Git client

### 1: Git Installation and Set Up GitHub
* Git installation:
    * Windows: Download and run the Git for Windows installer
    * Linux: In the terminal, use `sudo apt install git` or the appropriate package manager
    * macOS: With Homebrew: `brew install git`
* Registration on GitHub
    * Create GitHub account
    * Add a new SSH public key
        * `ssh-keygen -t ed25519 -C "your_email@example.com"`
    * Add Your new SSH key to Your GitHub account

### 2: Basic Git Commands
* Basic commands:
    * `git init`: Create a new repository
    * `git clone`: Clone an existing repository
    * `git add`: Add files to the staging area
    * `git commit -m "message"`: Commit changes with "message" commit message
    * `git status`: Check the repository status
    * `git log`: View commit history
* Additional commands
    * `git push`: Push local changes to the remote repository
    * `git pull`: Download remote changes and merge them into local code
    * `git fetch`: Download remote changes (without merging)
* Task:
    * Set up a simple project and practice using the above commands.

### 3: Collaboration and Branches
* Branches:
    * `git branch new-feature`: Create "new-feature" branch
    * `git checkout -b new-feature`: Also create "new-feature" branch
    * `git checkout new-feature`: Switch to "new-feature" branch
    * Merge:
        * `git checkout master`: Switch to "master" branch
        * `git merge new-feature` Merge "new-feature" branch into "master"
* Handling conflicts
* Task:
    * Create a new branch, modify some files, and merge it into the master branch.

### 4: Special Commands and GitHub
* Special commands:
    * `git revert`: Reverse the effect of a commit
    * `git cherry-pick`: Copy a single commit to another branch
* Pull request
* Task:
    * Create a GitHub repository and send a pull request.