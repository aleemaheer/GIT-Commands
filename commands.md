## Git commands 🚀
1. If we want to create a new file, we can create a file using terminal by typing command:
 ``` bash
    touch index.html
```
This is a linux command, this will create a new index.html file.

2. To create a new repository we use a git command which is written below:
 ``` bash
    git init
```

3. To put the user-name globally we use a git command which is written below:
``` bash
   git config --global user.name'Aleem Aheer'
```
this will puts the user name Aleem Aheer globally.

4. To put the user-email globally we use a git command which is written below:
``` bash
   git config --global user.email'aleemaheer5769644@gmail.com'
```
this will puts the user-email globally.

5. To add the file in the git repository, we use a git command, that is written below:
``` bash
   git add index.html
```
this will adds the index.html to the git repository.

6. To add all the html files to the git repository, we use a git command that is written below:
``` bash
   git add *.html
```

7. To add all the files in the git repository, we use a git command that is written below:
``` bash
   git add .
```
this will adds all the files in the git repository.

8. If we want to remove the file from the git repository, we use a git command that is written below:
``` bash
   git rm --cached index.html
```
this will remove the index.html file from the git repository.

9. If we want to check the git repository means that what's in the git or not, we use a git command that is written below:
``` bash
   git status
```

10. If we want to track the changes in the git repository, we use a git command that is written below:
``` bash
   git commit -m 'Initial commit'
```

11. If we want to clear the screen, following command is used:
``` bash
   clear
```
this will clear the screen, this is a linux command.

12. If we want to ignore the files. Than we have to make a file by writing the following command:
``` bash
   touch .gitignore
```
this will create a gitignore file, than we have to write the name of the file in the gitignore file that we want to ignore.Then check the status the file will be ignored.

13. If we want to create another branch, than we have to write the following git command:
``` bash
   git branch login
```
this will create a new branch named login.

14. If we want to switch to a different branch, we have to write the following git command:
``` bash
   git checkout login
```
this will switch into login branch.

15. If we want to merge a branch we can write a command like this:
``` bash
   git merge login
```
this will merge the login branch into the master branch.

16. If we want to add and commit the file in short way, we can write this command:
``` bash
   git commit -am "Initial commit"
``` 
this will add the all files and commit it.

17. If we want to track the history, that who changes and when we use a command that is written below:
``` bash 
   git log
```

18. If i want to check that how many i have total branches we can write this command:
``` bash
   git branch
```
this will list all the branches we have.

19. If we want to unstage the file from the git repository we can write this command:
``` bash
   git reset [name of file]
```
this will discard the changes in the file we have added.

20. If we want to unstage all files from the git repository we can write this command:
``` bash
   git reset
```
this will unstage all files from the git repository.

21. If we want to reset the commit, we can write this command:
``` bash
   git reset --hard <commit>
```
this will reset the commit.

22. If we have to pull or fetch the other branches from the remote, we can write command:
``` bash
   git fetch --all
```

23. To check how many origin i have use the following command: 
```bash
    git remote -v
```
24. To fetch the master branch from alt and pull it into your current head, do:
```bash
    git pull alt master
```
25. To push a specific remote use the command:
```bash
    git push -u <name of remote> <branch name>
```
this will push the specified branch to the specified remote.
26. If we want to remove a remote we can write the command:
``` bash
   git remote rm <name of remote>
```
27. To see the logs of commits, we can use the command:
``` bash
   git log
```
this will show the authoer name, date, commit message, commit id.

28. Also we can use another command to see the logs in detail:
``` bash
   git whatchanged
```
this will show the more details as compared to the result of command **git log**. 

29. If we want to remove a git repository, we can use the command:
``` bash
   rm -rf .git*
```
this will remove the git repository

30. If we want to revert the last commit we can use the command:
``` bash
   git reset soft HEAD~1
```
this will revert the latest commit, but the files will be remain staged.

31. We can rename a branch name by a command:
```bash
   git branch -m new-branch-name
```

## Making a repository on github

* First write a command to initialize a empty git repository by writing command:
``` bash
   git init
```
this will create initialize a empty git repository.

* Next we have to add the files and commit them.

* We can add files by command:
``` bash
   git add <name of file>
```
this will add a specified file

* If you want to add all the files in one command you can write:
``` bash
   git add .
```
this will add the files to the repository.

* Now we have to commit our changes by typing command: 
``` bash
   git commit -m "<commit message>"
```

* Now we have to add a remote to our repository by a command:
``` bash
   git remote add <name of remote> "URL"
```
this will add a remote to your repository, you will get the URL when creating a repository on github.

* Now we have add the files, committed them, added a remote (where it will be pushed) and now we have to push it to github, we can write the command:
``` bash
   git push -u <name of remote> <name of branch>
```
By default our first branch is master, so if you have only one branch you can write master in the branch name like this, assuming that you have a remote of name origin:
``` bash
   git push -u origin master
```

* We can also get these commands from the github when creating a new repository.

* Next time, if we have done some changes, we have to add the file, commit it and push it by typing this command:
``` bash
   git push
```
this will push the new files to the github.

* If we are working in a team then we can pull or fetch the other's team members code by typing command:
``` bash
   git pull
```
this will checks that everything is up-to-date, if not updated this will pull the code from the remote.

* If we want to clone a repository we can write a command:
``` bash
   git clone "URL"
```

😍 Made with 💗
😍 Thanks for reading 👋
😍 Please star this repository if you found this helpful 🔥