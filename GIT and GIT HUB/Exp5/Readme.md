Aim/Overview of the practical: To Merge pull request and update local repository on GitHub.


2. Task to be done: Creation local repository, create files, push and pull operations. 3. Steps for Experiment: -
1) Create a repository on local machine or clone a already created repository.
2) Now go to your repository by (cd <repo_name>) and run (ls) command to check for the files.
3) Now create a new file in your repository i.e. (vi Exp05.txt) and add some content inside the file, and also check for the data inside the file i.e. (cat <file_name>)
    
 4) Now after adding some content inside the file, add & commit the file. i.e. (git add .) & (git commit -m “your message”).
  05) Now before creating a new feature_branch from the main branch i.e. (git checkout -b <branch_name>), check for already created branch i.e. (git branch) i.e. (experiment5).
06) After creating a feature_branch open the same file which was created on the main_branch (vi Exp05.txt) and make some changes in the feature_branch.
   
 07) Now after making change in the same file, add & commit the file in the feature_branch. i.e. (git add .) & (git commit -m “your message”).
08) Now we can see the changes made in the feature_branch i.e. (git diff main <feature_branch>).
09) Now merge the feature_branch into the main branch i.e. (git merge <feature_branch>).
10) Now we can see the changes done in the feature_branch after merging it to main branch i.e. (cat <file_name>).
     
 11) Now push all the changes on the GitHub in the main branch i.e. (git push origin main).
 12) Now go to the feature_branch and open the same file and make some changes.
13) Now open the same file and make some changes and commit the changes.
    
 14) Now we can see the changes made on the GitHub.
 12) Now go to your GitHub account and open a pull request.
 13) Now merge pull request before merging it will check for the conflicts.
  
 14) Now the branch and the files are successfully merged.
 15) Now on the local repository we can also see the changes made on the Git and Github.
 We have successfully created a file and merged in the Main Branch.
Learning outcomes (What I have learnt):
1. Learnt about GitHub.
2. Learnt about Git.
3. Learnt about various git commands that can be applied on Git Bash.
4. Learnt about push and pull merge request.

