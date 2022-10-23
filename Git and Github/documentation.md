# Git and GitHub Documentation
## Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
## GitHub
While git is a service system, GitHub is one of the platforms which provide this service online. GitHub allows you to host your repositories online.
## Git Commands
- ```git clone``` ->  Creates a clone/copy of an existing repository into a new directory.
- ```git init``` -> To initial git repository in the present directory.
- ```git status``` -> Tells you about the untracked changes and staged changes in the repository.
					<br> &emsp; Red text is for untracked files whereas Green text is for staged files.
- ```git add filename``` -> To add the file with changes to the staging area.
					<br> &emsp; git add . -> To add all the unstaged files to staging area.

- ```git commit -m "Message" ``` -> To commit the stagged changes. In other words to make a checkpoint/save-point of the repository state.

- ```git restore --staged filename ``` -> To remove the file from the staging area without committing it.

- ```git log``` -> Shows the history and hash of all the commits that were made.

- ```git reset hash_of_the_commit``` -> Removes all the log of commit above the commit whose hash is mentioned.
					<br> &emsp; After git reset the files that were modified in the removed commits are now in the unstagged area or basically are currently untracked.

- ```git reset --hard hash_of_the_commit``` -> Removes all the file changes and leaves nothing untracked or unstaged.

- ```git restore filename``` -> brings back the files which were removed in git reset.
					<br> &emsp; the files lost in git reset can also be kept in the stash area.
					<br> &emsp; Stash is similar to a backstage area.

- ```git stash``` -> This removes the file from your directory and stashes it without commiting.
					<br> &emsp; In other words moves the file from your directory to a temporary waiting area / stash area(or backstage).

#### &emsp; &emsp; Note: In order to stash some file, you need to bring the file first to the staging area by git add filename and then stash them.

- ```git stash pop``` -> Brings the changed files from the stash area to the unstaged area.
					<br> &emsp; It brings the files from stash to your directory.

- ```git stash clear``` -> Removes the files from stash area and deletes them forever.

- ```git remote add origin url``` -> To connnect the remote repository (say on your GitHub profile) url to the local repository.
					<br> &emsp; Here origin is set as the name of that url.
					<br> &emsp; By convention all the repositories in your personal account have a url name as origin.

- ```git remote -v ```-> Shows all the urls attached to that local repository.

- ```git push origin master``` -> To push the changes to the origin url's master branch.
					<br> &emsp; Origin is the name of the url of our github repository.
					<br> &emsp; Master is the branch name of the repository.
					<br> &emsp; In modern versions the master branch is also called main branch, so do consider that as well.

- ```git branch newbranchname``` -> Creates a new branch.

- ```git checkout branchname``` -> Points the head to the branchname which is specified.
					<br> &emsp; Head is a pointer that points to the branch on which the commits will be added

- ```git merge branchname``` -> To merge the specified branch into the main branch.

- ```git remote add upstream url``` -> Adds the url as the upstream url.
					<br> &emsp; The source from which we have forked is called the upstream url and origin is the url of the repository which is in your personal github account.
- ```git pull``` -> To pull/fetch the changes from the original online repository (or the source of fork) to the local repository.

- ```git pull upstream main``` -> pulls data and commits from the upstream to your local repositories main branch
#### &emsp; &emsp; Note: In this case only the local is updated, your online forked repository is still not updated, to update it use ```git push origin main```.

- ```git rebase -i hash_of_commit_whose_upper_commits_need_to_be_squashed``` -> -i is for interactive mode.
					<br> &emsp; This will open an interactive screeen where you can change pick to s, for squashing that commit into the commit above it which is pick.

### Extras 
If a branch has been used to create a pull request then whatever changes you commit on that branch gets added to that pull request.
In other words, one branch can have one pull request only.
That is why it is advised to create a new branch for every feature or bug that you are working on.
So that you can open different pull requests for different features in the same project and the code base stays more organized and create pull request from that specific branch of your fork to the main branch of the original project.




