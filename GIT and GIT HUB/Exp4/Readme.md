Aim/Overview of the practical: Editing a file and committing changes on GitHub.


2. Software Used: Git Bash, GitHub.
3. Steps for experiment/practical:
❖ Create or clone a repository on your local machine and open GIT BASH.
 ![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/ea7fd2c5-3e18-4133-973c-264ff2220c31)

❖ Move to the directory using the cd command.
❖ Create or open a file in the master or main branch , eg , file.c and add some text to
the file.
❖ Add the file to the staging area using git add and then commit the changes using the
git commit command.

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/9261e1dc-341d-4b0e-b053-677605cc7126)

❖ Pull the changes to the remote repo using the command git push <remote_name>
<branch_name>.(In Mac the push don’t occur because of ssh permission).

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/6d695760-726d-4d21-906d-e04078e693e1)

❖ You will be able to see the changes in the remote repository.
( local ) ( remote )

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/d2a185b5-41b5-4a2f-af54-e13ec0948466)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/b5f83ee9-8440-4447-9c07-04c3fa75b47e)

❖ Now, make some changes in the file in the remote repository and pull those changes in
the local repository

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/40ae08b5-6525-47e9-a977-1cd4a4e4d152)
.
( remote ) ( local )

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/e0bc1ba8-a20e-4632-ba86-c5ee13faa495)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/bf211c10-0886-49c4-9961-a5179140d1da)

❖ Create a new branch and checkout to it using the git checkout -b command , eg , test.
❖ Open the file.c on the vi editor and make some changes in it.

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/13d5eea1-f587-42a2-81d3-e79155dfdb0a)

❖ Merge the changes made in the test branch with the master branch and resolve the
conflicts manually if necessary.
❖ Push the master and test branch onto the remote repository
You will be able to see the new changes in the remote repository.
( local ) ( remote )

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/77f14547-2c62-4c87-af04-e53d7f86210e)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/fa2aea22-2d16-49ff-89f8-5e487e59ebbe)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/28ef4bd7-7d81-4eaf-a972-867681fbea6e)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/ac2ef3cc-de30-4cb4-a45b-4cef796e572d)

❖ Now, Go to github, open the repository and move to the test branch and make some
changes in a file.
❖ Commit the changes and move to the master branch. Click on the Compare &
Pull request.
❖ Create the pull request, resolve the merge conflicts (if any) and then merge pull
request.

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/126e08c9-a828-4299-b9fe-2877622f80e5)

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/6cc5f5c9-85eb-4a16-afa7-13dfc362a3b8)

❖ After the merging, you may choose to delete your branch , i.e , test
❖ Now, pull the changes to the local repository using git pull.

![image](https://github.com/Tarushchauhan73/Practical-sem_4/assets/156651501/edece26c-e7d7-4eb9-82eb-ddd87dff4fc4)

❖ You will be able to see the changes in your local repository.
( remote ) ( local )
❖ Result/Output/Writing Summary
❖ In this experiment, we have edited a file in the local repository and shown the changes
on the remote repository and vice versa. For this purpose, we have made use of both
Git and GitHub.
Learning outcomes (What I have learnt):
1. Learnt how to create a branch.
2. Learnt how to push the changes to the remote repository.
3. Learnt how to pull the changes from the remote repository.
4. Learnt to merge two branches.
5. Learnt how to resolve merge conflicts.
