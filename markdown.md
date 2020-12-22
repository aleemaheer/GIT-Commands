# Git commands :
1. touch command => this command is not a git command. This is a linux command to create a new file. Syntax
 ``` bash
    touch index.html
```
this will create a new index.html file.

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
this will clear the screen.

12. If we want to ignore the files. Than we have to make a file by writing the following command:
``` bash
   touch .gitignore
```
this will create a gitignore file, than we have to write the name of the file in the gitignore file that we want to ignore.Then check the status the file will be ignored.

13. If we want to create another branch, than we have to write the following git command:
``` bash
   git brach login
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

#

## Making a repository on github

If we want to make a repository on github, than we have to write:
``` bash
   git remote add origin "URL"
```
Next step is to write another git command that is written below:
``` bash
   git push -u origin master
```
We can also get these two commands from the github when creating a new repository.

If we want to push new files to the github repository we can just write the following git command:
``` bash
   git push
```
this will push the new files to the github.

If we want to check that everything is up-to-date, we can write this command:
``` bash
   git pull
```
this will checks that everything is up-to-date.

If we want to get the files from the github repositories we can write this command:
``` bash
   git clone "URL"
```

Thanks for reading this.
