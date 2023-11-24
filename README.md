# 3.2 Introduction to GIT II

## Deliverables

### What is GitHub Authentication and how what methods available to be implemented?

GitHub Authentication refers to the process of verifying the identity of users by providing unique credentials to GitHub before users can access certain resources on GitHub.

GitHub Authentication methods available to be implemented as follow:
* Username and password only: Users can log in to GitHub via their individual username and password, a common method for most users.
* Two-factor authentication (2FA): 
  

### Update the Readme file to contain least 15 github commands and what are the usage of them?

Set Your Name and Email Address. These settings will be used to identify your commits in the Git history.
``````````````````````````````````````````````````````````````````````````````````````````````````````````
git config --global user.name "[Your Name]"
``````````````````````````````````````````````````````````````````````````````````````````````````````````

``````````````````````````````````````````````````````````````````````````````````````````````````````````
git config --global user.email "[youremail@example.com]"
``````````````````````````````````````````````````````````````````````````````````````````````````````````
\
Stage all the files for commit to your local repository by the following command.
`````````````````````````````````````````````````````````````````````````````````````
git add .
`````````````````````````````````````````````````````````````````````````````````````
\
Change an existing file path and stage the move.
`````````````````````````````````````````````````
git mv [existing-path] [new-path]
`````````````````````````````````````````````````
\
Delete the file from project and stage the removal for commit.
```````````````````````````````````````````````````````````````
git rm [file]
```````````````````````````````````````````````````````````````
\
Commit the file that you’ve staged in your local repository.
`````````````````````````````````````````````````````````````
git commit -m "[descriptive message]"
`````````````````````````````````````````````````````````````
\
Unstage a file while retaining the changes in working directory.
```````````````````````````````````````````````````````````````
git reset [file]
```````````````````````````````````````````````````````````````
\
Push the changes in your local repository to GitHub.
`````````````````````````````````````````````````````
git push origin main
`````````````````````````````````````````````````````
\
Show modified files in working directory, staged for your next commit.
``````````````````````````````````````````````````````````````````````
git status
``````````````````````````````````````````````````````````````````````
\
Diff of what is changed but not staged.
````````````````````````````````````````
git diff
````````````````````````````````````````
\
Compare the file version in your working directory with the file version last committed in your remote repository. The HEAD in the git command refers to the remote repository.
```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
git diff HEAD [filename]
```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
\
Fetch down all the branches from that Git remote.
``````````````````````````````````````````````````
git fetch [alias]
``````````````````````````````````````````````````
\
Retrieve an entire repository from a hosted location via URL.
`````````````````````````````````````````````````````````````
git clone [url]
`````````````````````````````````````````````````````````````
\
Fetch and merge any commits from the tracking remote branch.
````````````````````````````````````````````````````````````
git pull
````````````````````````````````````````````````````````````
\
List your branches. a * will appear next to the currently active branch.
````````````````````````````````````````````````````````````````````````
git branch
````````````````````````````````````````````````````````````````````````
\
Create a new branch at the current commit.
``````````````````````````````````````````
git branch [branch-name]
``````````````````````````````````````````
\
Switch to another branch and check it out into your working directory.
``````````````````````````````````````````````````````````````````````
git checkout
``````````````````````````````````````````````````````````````````````
\
Merge the specified branch’s history into the current one.
``````````````````````````````````````````````````````````
git merge [branch]
``````````````````````````````````````````````````````````
\
Show all commits in the current branch’s history.
`````````````````````````````````````````````````
git log
`````````````````````````````````````````````````
### What are the 4 Github commands that you think you will use the most in the real project and why? Explain it on the readme file.

### Push the changes you made to your repository. with different commit.


















### References
https://kinsta.com/knowledgebase/install-git/
\
https://github.com/su-ntu-ctp/6m-cloud-3.1-introduction-to-git-i/blob/main/CE%203.1%20Introduction%20to%20GIT%20I.pdf
\
https://education.github.com/git-cheat-sheet-education.pdf
\
https://www.educative.io/answers/what-does-git-diff-head-filename-do
