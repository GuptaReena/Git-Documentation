# Git-Documentation
Git Documentations

----> GitHub,GitLab,Bitbucket VS Git:



Git : It is a version control system that track changes for hosted software's code on repositories like GitHub,Gitlab,BitBucket

GitHub,Gitlab,BitBucket : Code repository for hosting platform for software Development(eg:- Website)

GitHub : It is a platform and a couldbase 



GIT AND GITHUB

Git : To configure the git using cli 

		--> git config --global user.name "Reena Gupta"

		To congigure the gamil by which the account has been created

		--> git config --global user.eamil "reenagupta1417@gmail.com"

		To view the configuration till here we use command

		--> git config --list



Git Baasic Commands

	Clone : clone a repository on our local machine

		--> git clone <-some link->

	Status: Display The state of the code

		-->git status 

modified : The file you have modified
unmodified: There is no change in the file
untracked : New file that git dosent track yet
modified : changed
staged : your file is ready to be commited

 Add & Commit
--> add :  Adding new file or modified file in your working directory 

--> git add file name or git add .   : It means that we can add all of the file together at a time

--> Commit: It is the record of the change

--> git commit -m "Meaningfull message"

--> Push Command: Upload local repository content to remote repository content . The file in which we were modifiying on our local machine now we have to put it on the remote access we use push command

--> git push origin main

	-> Uncoding Changes
 
	-> staged change
 
	-> git reset file name
 
--> commiteed change(for one commit)
	-> git reset HEAD~1
 
	-> commited changes(for many commits)
 
	-> git reset <- commit hash ->
 
	-> git reset --hard <- commit hash ->
Branch Command 

git branch (to check branch)

git branch -M main (to renaim the branch)

git checkout <-branchname ->(to naviag

git checkout -b <-new branch name->(to create new branch)

git checkout -d <-branch name -> (to delete branch) 

Merge Code

There is 2 ways

	git diff <- branch name -> (to compare commits,branches, files& more

	git mere <- branch name -> (to merge 2 branches)



2 way

create a Pull Request(PR)

Pull Request : It lets you know other chnages you've pushed to a branch in a repository on github



Fork : It is a rough copy 

			--> A fork is a new repository thst shaes code and visibility setting with the original "Upstream"


Task 2 : Publshing code on GitHub using GitHUb Pages

		Step1: Make minor changes to your project in angular.jason

				outputPath : "dist/coms" to "docs"

		Step2: Open command prompt/terminal of vscode in the working directory where project resides

				run the command : ng build --outputPath docs -base-href ProjectName

		Step3: Open git bash on same directory as project directory

						git add .

						git add origin "https://github.com/guptareena/fsd.git"

						git commit -m "docs for hosting Web page"

						git push -u origin main


