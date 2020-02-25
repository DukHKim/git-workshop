# git-workshop
Learn the basics of git, a popular Version Control System used by many developers around the world.


## Get Started

### Installing git


First things first, install [git!](https://git-scm.com/downloads). 

#### Windows
All of the git commands will be done through the `git bash` program, so make sure you have that open.

#### Mac
Open up the terminal app! 
You can check if you already have by running:
```
git --version
```

Also, create an account [here](https://github.com/) if you don't have one already.

Finally, set up SSH on your github account by following these [two](https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) [links](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account).



## Bash 

### Anatomy of a bash command

`command --options/flags ARGUMENTS`


### Basic Bash Commands

`ls`(**l**i**s**t): Lists the current files and directories

`cd DIRECTORY`(**c**hange **d**irectory): Changes directory to given directory 
`.` is an alias for the current directory
`..` is an alias for the parent directory

`mkdir DIRECTORY_NAME`(**m**a**k**e **dir**ectory): makes a directory with the given path and name. If no path is given, assume current directory.
`touch FILE_NAME`: Creates a file with the given name


## What is git?

Git is a popular Version Control System (VCS). In essence, it is nothing more than just a history of changes. 


### Definitions

*def* **repository**: All of the data stored inside a project directory, stored in `.git/`.

*def* **commit**: a commit object is a snapshot of code at a given time. It contains file changes, references to other commits, and a SHA1 name.

*def* **branch**: A series of commits off of a specific point in time (commit) in the master branch.

*def* **staging**: Preparation area for file changes to be committed.


### Basic Commands

`git pull`: Shorthand for two commands, `git fetch` and `git merge FETCH_HEAD`, this is how you apply commits from another branch into the current working branch.

`git add`: Add outstanding changes to staging area in the current branch. Choose which file changes you want to keep.

`git commit`: Turn the staged changes into git commits. Can be seen as documenting and "committing" to the changes you've made. 

`git push`: Update remote branches with local changes. Use this to move commits from your local machine to the remote repository.

`git clone`: Create a local copy of a remote repository

## Workshop Activity
- Create a personal repository
    - `git init`
    - create `README.md` file
    - `git add README.md`
    - `git commit -m "First commit!"`
    - `git remote add origin [GIT_REPOSITORY_URL]`
    - `git push -u origin master`
- Branch off of workshop repository
    - `git clone git@github.com:DukHKim/git-workshop.git`
    - `git checkout -b BRANCH_NAME`
    - Mark off attendance, add a link to your remote repository
    - `git add README.md`
    - `git commit -m "NAME is here!"`
    - `git push -u origin BRANCH_NAME`
    - Merge branch on github
    
## Attendance
jacob

ethan

julie

caleb

chris

[carissa](https://github.com/carissamok/first-respos.git)




## Helpful Links

[Markdown Cheat Sheet](https://guides.github.com/features/mastering-markdown/)

### Git Tutorials
https://git-scm.com/docs/gittutorial

http://rogerdudler.github.io/git-guide/

https://developer.ibm.com/technologies/web-development/tutorials/d-learn-workings-git

https://www.sbf5.com/~cduan/technical/git/git-1.shtml
