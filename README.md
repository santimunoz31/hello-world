# hello-world
First github repository, for learning purpose only

# About this repo
The thing I am currently learning is to make commits of the changes I make in the repo, I still don't know how to do it in the command line

## Git initial configuration
first you have to download git to your computer, in linux is simply by writing on your terminal the command:

`sudo apt install git-all`

After installing you must configure your username and email for identification:

Username is:

`$ git config --global user.name "USER NAME"`

email is:

`$ git config --global user.email "your@email.mail"`

Then we will configure the default initial branch of any repository:

`$ git config --global init.defaultBranch main`

Once you have set this up is time to create your first repository.

## Creating repository

Change to the directory you want to make your repository an type the command:

`git init`

This will create a repo in that location. Then creat a .gitignore file and write in the /build folder.
next:

`git add .`

To add all the content of the folder to the git repo in staging phase, but it still the commit left, for that we type:

`git commit -m "COMMIT MESSAGE"`

To skip the staging:

`git commit -a -m "COMMIT MESSAGE"`

## Working with branches

To make a new branch:

`git branch BranchName`

Now the branch is created we must switch first to it:

`git switch BrachName`

For merge, step into the main branch:

`git merge -m "MERGE MESSAGE" BranchName`

For creating and switching at the same time:

`git switch -c BranchName`


## Github and Git

Add repo to git:

`git remote add origin https://github.com/santimunoz31/agv-jr.git`

`git branch -M main`

`git push -u origin main`

To allow the connection between github and git:

`gh auth login`
