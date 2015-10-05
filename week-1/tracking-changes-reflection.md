#1.5 Tracking Changes

**1. How does tracking and adding changes make developers' lives easier?**
It makes developer's lives easier because this allows then to work simultaneously on a single file and find out which particualr changes were made by who at any given point. This will allow them to easily pinpoint when a bug for example occured (and easily pinpoint the bug itself). It will also allow them to rollback to an earlier version of the file if they need to.

**2. What is a commit?**
A commit is basically a snapshot, a saved state. To "commit" changes is to record changes in the local directory.

**3. What are the best practices for commit messages?**
Commit messages has to be descriptiive. Someone who will later access the repository has to understand what changes are being made at a particular commit. Some best practices are:
  - Keep the commit message short, usually around 50 characters. Capitalize the first word and use imperative mood. (aka Subject).
  - If more explanation is needed, start another paragraph after the subject that has a more detailed explanation of the commit.

**4. What does the HEAD^ argument mean?**
 This is usually used after the git reset command to go back to the last commit. HEAD^ is a shortcut for "HEAD^1" which means go back to the last commit.

**5. What are the 3 stages of a git change and how do you move a file from one stage to the other?**
  1. *Working* - This means that you are currently working on a file in the current branch.
  2. *Stage* - Before you commit a file, you must "git add" it first to the staging area. This means that changes are ready to be committed to a particular file. A snapshot of the file is created (but not yet saved). You can also unstage the file if you determine that you need to make further changes before doing a "git commit"
  3. *Commit* - done by doing a "git commit". This is where the snapshot is saved.

**6. Write a handy cheatsheet of the commands you need to commit your changes?**
- `git add [file]` - adds a file into the staging area, creates a snapshot of a file in preparation of versioning.
- `git status` - lists all new or file changes that needs to be commited
- `git commit -m "message"` - saves a snapshot of the file in the local repo
- `git reset [file]` - removes the file from the staging area, deletes the snapshot (but preserves the file)
- `git push origin master` - uploads local commits to Github

**7. What is a pull request and how do you create and merge one?**
Pull requests lets others know about changes you've pushed to a repository on GitHub. After pushing a commit to a forked repo into GitHub, navigate to your repository with the changes you want someone else to pull and press the Pull Request button. Others will be able to review changes, discuss it or even submit further commits before merging to the master.

**8. Why are pull requests preferred when working with teams?**
Pull requests are preferred because it allows changes to be reviewed and discusses before being merged to the master.