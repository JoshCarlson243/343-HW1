# 343-HW1
Git repository for homework assignment 1 in CIS 343

The main commands used to interact with git include:

git init - initializes a new git repository locally

git add <filename> - tells git to add this file to staging, in other words, it adds this file to the list of files that are kept track of by your repository

git commit - finalizes the staging process and saves any changes you made to the files within your repository

git push - if you are connected to a github repository, this will publish your local staged files to your github repository.

git checkout -b <branchname> - creates a new branch within your repository.

git pull - pulls all the files tracked in your github repository into your local git repository

git clone <repository ssh address> - clones a github repository locally, which also allows you to push changes in files to the github repository.

Example:
To add a local file named "empty_text.txt" to this repository, we can first:

git clone git@github.com:JoshCarlson243/343-HW1.git - this clones this git repository to your local machine.

git add empty_text.txt - stages empty_text.txt to be committed.

git commit - commits your changes to the git repository.

git push - pushes committed changes 

This should push the file "text_file.txt" to the github repository.



![image](https://github.com/user-attachments/assets/6444e888-6f89-47ea-ad7a-2e6e1d3ab650)

