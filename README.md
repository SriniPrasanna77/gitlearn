# gitlearn

Learning git

git init
Git remote add origin "<link to GitHub repo>"
Git pull origin main //main => name of main/master branch on GitHub
Git status
Git log
Git add <filename>
git commit -m "newsample file on 23/jul/2022"
Git add -A //to commit all changed/new files
Git commit -a

Git branch <branch-name>
Git checkout <branch-name>
Ls lists file in the current branch

Git checkout main

To merge branches, make sure to be in the target branch
Here, we are in main branch as we want the firstbranch to be merged into main branch

Git merge firstbranch

Rebase branches

Git rebase <branchname> // current branch will be updated with the changes from rebase branch

Git push

We can use ssh to push changes

1. Generate ssh public key
Ssh-keygen
Get the ssh key (pub key)
In GitHub profile settings, add the ssh under ssh and gpg keys


Git push origin <branchname>