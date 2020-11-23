# Git Basic Commands:-

1. To Initialize a folder as git repo use- ```git init```	
2. To set global username for the initialized folder- ```git config global user.name "YOUR_USERNAME_OF_GITHUB" ```
3. To set the user email for the initialized folder-```git config global user.email "YOUR_EMAIL"```
4. To commit your changes with a message- ```git commit -m "YOUR_MESSAGE``` 
5. To add a repo for the desired folder-  ```git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git```
6. This command will merge the pull request when there is no history available between previous and new data:-```git pull origin master --allow-unrelated-histories```
7. To change the remote origin of current directory- ```git remote set-url origin https://github.com/yourusername/yourreponame.git```
	* In case You want to remove remote origin use command- ```git remote remove origin```
8. Add a file to stage commit- ```git add filename.txt```
	* to enter all the files to stage commit use command- ```git add . ```

# Git ignore files related command:-

1. add a file named .gitignore when you doesn't want to push few files/folder in github repository.
2. In .gitignote file add following lines to exclude the files/folder - ```use *(End character of file) to remove those file which end with this character for example:- *.php ```
3. to remove a folder insert this line - ```foldername/```
4. you can use ! also to not ignore a file.
5. when you already commited the file and want to remove that file after adding gitignore from github use command:- ```git rm -r --cached FILENAME```
	* for more details refer to the [website](https://www.pluralsight.com/guides/how-to-use-gitignore-file)
	* [Website1](https://stackoverflow.com/questions/19663093/apply-gitignore-on-an-existing-repository-already-tracking-large-number-of-file)
	* [website2](https://stackoverflow.com/questions/43762338/how-to-remove-file-from-git-history)

# Git branching related commands:-
1. Switch to a new branch - ```git checkout -b "BRANCH_NAME"```
2. Refer to this link for branching update - [Link](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
	* Clone a branch directly - ```Git clone -b <branchname> <url>```
3. To check which remote branch you have attatched to your folder -``` git remote -v```


# Abort the local changes in git repository:-

1. Discard all local changes, but save them for possible re-use later: ```git stash```
2. Discarding local changes (permanently) to a file - ```git checkout -- <file>```
3. Discard all local changes to all files permanently - ```git reset --hard```



# Git Readme Profile Tips:-

1. Apply no of profile visits batch:- ```https://pufler.dev/git-badges/```
2. Apply Hi Image GIf - ```<!img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">```
	* Note - Remove ! from image tag
3. view raw file of your github profile:-``` https://github.com/<username>/<username>```
4. [More Info](https://github.com/MartinHeinz/MartinHeinz/blob/master/README.md)
