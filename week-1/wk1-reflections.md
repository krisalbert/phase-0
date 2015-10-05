#1.1 Think About Time

Starting Dev Bootcamp has been surprisingly more challenging than I had anticipated. Because my motivation and excitement level was really high when I was applying, I thought that this would just fly by and I would be able to do all the tasks I need to do for DBC with no issues. My motivation and excitement level remains high, but now that I am actually doing it, trying to focus on doing this as well as other stuff that are going on in my life - work, trying to move to SF, and other stuff that pops in unexpectedly, doing DBC has not been as easy to me as I had assumed it was going to be.

Starting a new habit is difficult, and starting DBC means creating a bunch of new habits that will prepare me not only for the onsite program, where I will be coding long hours each day, but also for a new career. It is a seemingly daunting task and I find myself sometimes being quite anxious about the road ahead. The key to starting a habit is to start very small. I started a new one this week while doing week 1 of phase 0 - meditating everyday. Because I am still not used to doing it, I actually missed a couple of days of it. No matter, I will continue doing it until it sticks. This is similar to what I experienced when I first started biking about 2 years ago; I had to force to get on the bike at least 3x a week and before I knew it, I was biking everyday to work and everywhere else too.

Studying on my own and finding the time to find it is still difficult for me. There’s just so many distractions and I need to learn to tune them out. Meditation hopefully will help with that in time, but for now, just carving out the time to force myself to do something instead of procrastinating and turning off all the distractions like text messages, Facebook, emails, youtube.

One technique that I had started using for a couple of months now (not always very successfully) is the Pomodoro technique. This is a timeboxing technique, meaning I will work for a set a mount of time (for example 3 pomodoros of 25 minutes each every night) instead of continuing to work until a goal is reached. Timeboxing is useful because it forces you to be more efficient since you know you only have a set of time allowed for a particular set of tasks.

As for how I am planning to study for phase 0, I will try to study for 3 pomodoros each weeknight and for 5 pomodoros on both Saturday and Sunday. I will look at what I need to do first and then decide how much time I should devote to a particular task and try to stick to that. Hopefully this works out, it will be difficult at first and I may fail to stick to my plan but hopefully by the time I get to the onsite part, I would’ve cut down my procrastination by a lot.

#1.2 The Command Line

**1. What is a shell? What is "bash?"**

A shell is an application that provides a command line interface wherein you can type and run commands from. There are many types of shell and bash is one of them. Bash means “Bourne again shell”, which is a re-write of the original Bourne shell. Bash is the most common unix shell and it is the default shell that ships with most Linux flavors as well as OS X.

**2. What was the most challenging for you in going through this material?**

I use the command line at work but there are a really only a few that I use a lot. Some of the commands that were discussed I am not familiar and so it’s just a matter of also getting familiar with these commands and thinking of specific instances where I would use them.

**3. Were you able to successfully use all of the commands?**

Yes, I tried to use all of the commands.

**4. In your opinion, what are the most important commands and arguments to know?**

Probably the ones that you would use to navigate through the file system and list the contents are the most important ones, especially for beginners. Commands like ls, pwd, cd are essential. Help is also very useful as it provides a lot of information about different commands and their usage.

**5. Can you remember what each of the following does of the top of your head? Write what each does.**

-`pwd` - Lists the present working directory or where you are in the command line.

-`ls` - lists all files and directories in the directory you are currently in or a particular directory if you specify one.

-`mv` - move a file or files from one particular location to another. This command can also be used in renaming a file, essentially “moving” the file from one filename to another.

-`cd` - cd is used when navigating the file system either going deeper or out of directories.

-`../` - this is to go one level up to the parent directory.

-`touch` - this is a command to create a new, empty file.

-`mkdir` - this command is use to create a new directory.

-`less` - less is a terminal pager program that allows you to display the contents of a particular file. It is similar to more but it has backward and forward navigation.

-`rmdir` - this command is used to delete a directory.

-`rm` - this command is used to delete a file.

-`help` - you can use this to display the information for a particular linux command. It will display information about the command as well as the usage.

#1.3 Introduction to Version Control

**1. Write an explanation of and compare git and GitHub to one another.**

Git and Github are almost always tied to one another so it can get confusing about where git ends and github begins and vice versa. Git is a version control software that live locally in your computer. Github meanwhile is a hub for git repositories. It allows users to store their repositories in a central place online. This makes collaboration a lot easier.

**2. Explain what version control is and how GitHub helps with it.**

Version control allows you to keep track of changes you made to files in your system, essentially creating snapshots of them in a given point in time. This allows you to work on files, create a snapshot, make another change, take a snapshot and so on. Another way of looking at this is using the "save as" function and creating multiple versions of a file manually (ie, v.01, v.02, etc). Github helps with this as a version control system like git is more efficient and less cumbersome than saving multiple copies of files with different versions and instead of creating multiple versions of your file manually, you can just have git deal with all that.


**3. Why do developers use version control (git)?**

Developers use version control system to keep track of changes. It also allows them to collaborate easier. Two or more developers can be working on the same file and git will be able to keep track of what changes each one made and at a later time, merge all of the changes. If there are conflicting changes, git will ask you to decide which one it should use. Since it creates different versions of the file, you can rollback to an earlier version if need be, or easily determine what changes were made in the current file and by who.

**4. What is a commit?**
A commit is basically snapshot. It is to record changes in the local repository.

#1.4 Create, Fork, and Clone Repositories

**1. If you were going to write instructions for a new person on how to create a new repo, fork a repo, and clone a repo, what would they be? Why would you fork a repository as opposed to create a new one?**

I thought the instructions in the course material was pretty straightforward in how to create, fork and clone a repo. I think it would probably be pretty similar to what was provided in there. I would probably include screenshots of what to type in the command line to make it even easier, although it is good to figure stuff on your own and get a better understanding of the material.

You would fork a repository instead of creating a new one if you want to make a copy of an already existing repository. You can then make changes to the contents of the repository without affecting the original one.

**2. What struggles did you have setting up git and GitHub? What did you learn in the process?**

One thing though that I made a mistake on was when cloning, I created a directory for the repositories that I created (one directory for `phase-0` and another for the forked `p0-cli`). I changed into those directories I just created and then cloned the repo. What it did was create a new directory inside the ones that I just created. I found out after doing this exercise that I don’t need to create those directories because git will create it automatically for me when I clone.

