# Test Repo for letting people practice using GIT

## Basic Workflow

**1. clone this repo**

From the terminal, from the folder you want this repo to be in (probably `C:\Users\<UserName>\Desktop\code\`) run:

`git clone https://github.com/AlexWKinley/awk_git_practice`

**2. Make a new branch**

go into the repo `cd awk_git_practice`

and then the command to make a new branch is:

`git switch -c <new_branch_name>`


**3. Make your changes**

Open up a text editor or similar and make a new file, and put whatever inside that file.

From the terminal, you can run `git status` to see what the state of your repo is. You should see it say you have one untracked file, and that you can use `git add <file>` to prepare that file to be committed.

Use the `git add` command to prepare the file to be commit.

You can run `git status` again to see that it should tell you something different this time. 

Then commit your changes with `git commit -m"<your commit message>"`

**4. Push your changes**

Now you should be able to run `git push` to send your new commits to github.


