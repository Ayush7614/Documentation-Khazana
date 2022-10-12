# Git and GitHub Documentation
## Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
## GitHub
While git is a service system, GitHub is one of the platforms which provide this service online. GitHub allows you to host your repositories online.
## Git Commands
- ```git init``` to initial git repository in the present directory
- ```git status``` to tell you about the changes which are yet not added or are untracked by git as of now or they are in the unstagged area
	It also shows files in the staging are
	Red color - files not in the staging area
	Green color - files in the staging area
	It shows no file if all the files and changes are already committed
- ```git add``` -> to add the files or changes to the staging area
	add works on the changed files only
	git add . -> to add all
	git add filename -> to add particular file

- ```git commit -m "Message" ``` -> to commit. to take a snapshot of the current state

- ```git restore --staged filename ``` -> to remove the file from the staging area without committing it

- ```git log``` -> shows the history of all the commits that were made

- ```git reset hash_of_the_commit``` -> removes all the log of commit above the commit whose hash is mentioned
	to get the hash of commits use git log
	after git reset the files that were modified in the removed commits are now in the unstagged area or basically are currently untracked

- ```git reset --hard hash_of_the_commit``` -> removes all the file changes and leaves nothing untrackked

- ```git restore filename``` -> can bring back the files which were removed in git reset
			the files lost in git reset can also be kept in the stash area
		stash is like a backstage

so in order to stash some file, you need to bring the file first to the staging area by git add filename
and then
- ```git stash```
This removes the file from your directory and stashes it without commiting
in other words moves the file from your directory to a temporary waiting area (or backstage)

- ```git stash pop``` -> brings the changes from the stash area to the unstaged area, ready to be staged.
	It brings the files from stash to your directory

- ```git stash clear``` -> removes the files from stash area and deletes them forever

- ```git remote add origin url``` -> to connnect the remote repository url to the local repository and the name used is origin
	here origin is the name of the url
	by convention all the repositories in your personal account have a url name as origin

- ```git remote -v ```-> shows all the urls attached to that folder or local repository

- ```git push origin master``` -> to push the changes to the origin url's master branch
	origin is the name of the url of our github repository
	master is the branch name of the repository
	in modern versions the master branch is also called main branch, so check that out

- ```git branch newbranchname``` -> creates a new branch

- ```git checkout branchname``` -> points the head to the branchname which is specified
	head is a pointer that points to the branch on which the commits will be added

- ```git merge branchname``` -> to merge the branchname branch into the main branch

- ```git remote add upstream url``` -> adds the url as the upstream url
from where we have forked is called the upstream url and origin is the url which is in your personal github account

push goes to your personal remote repository ie origin
and pull fetches from the upstream url repository from where you forked

### Note 
If a branch has been used to create a pull request then whatever changes you commit on that branch gets added to that pull request.
In other words, One branch can have One pull request only.
That is why it is advised to create a new branch for every feature or bug that you are working on.
So that you can open different pull requests for different features in the same project and the code base stays more organised
and create pull request from that specific branch of your fork to the main branch of the original project.

### Note
If you want to get back to a previous commit stage then use
	git reset hash_of_commit
at this point your changed files will be unstaged.
stage them with
	git add .
and send them to stash area
	git stash
now you will have the exact same structure as the commit whose hash you have entered

git reset is used to delete commits from commit history ie the log.

Now if you want to push this to your online repo which is already some commits ahead as you have reset back to commit
You will have to force push the changes and all the commits on the online will be overridden with your local commit log
	git push origin branchname -f