# 3.2 Introduction to GIT II

## Deliverables

### What is GitHub Authentication and how what methods available to be implemented?

GitHub Authentication refers to the process of verifying the identity of users by providing unique credentials to GitHub before users can access certain resources on GitHub.

GitHub Authentication methods available to be implemented as follow:
* Username and password only - Users can log in to GitHub via their individual username and password, a common method for most users.
* Two-factor authentication (2FA) - GitHub generates an authentication code any time someone attempts to sign into your account on GitHub.com. Thus, the only way someone can sign into your account is if they know both your password and have access to the authentication code on your phone.
* Passkey - Add a passkey to your account to enable a secure, passwordless login. Passkeys satisfy both password and 2FA requirements, therefore you can complete your sign in with a single step.
* SAML single sign-on
* Authenticating with GitHub Desktop
* Authenticating to the API with a personal access token - To use GitHub REST API for personal use.
* Authenticating to the API with an app - To use the API on behalf of an organization or another user.
* Authenticating to the API in a GitHub Actions workflow
* Authenticating with the command line - via HTTPS, SSH

### Update the Readme file to contain at least 15 GitHub commands and what are the usage of them?

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
### What are the `4 GitHub commands` that you think you will use the most in the real project and why? Explain it on the readme file.
* `git add .` - Stage all changes made to files in the working directory for the next commit.
* `git commit -m` - Records changes to the repository with a descriptive commit message.
* `git push` - Uploads local changes to the remote repository for collaboration.
* `git pull` - Updates the local branch with changes from the remote repository to stay synchronized with the latest developments in the project.

The above 4 commands facilitate effective collaboration, version control, and project management in a Git-based development environment.

### Push the changes you made to your repository. with different commit.

Refer to https://github.com/JasonWu2O23/github-3.2-wu-jinqing/commits/main

## References
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github
\
https://kinsta.com/knowledgebase/install-git/
\
https://github.com/su-ntu-ctp/6m-cloud-3.1-introduction-to-git-i/blob/main/CE%203.1%20Introduction%20to%20GIT%20I.pdf
\
https://education.github.com/git-cheat-sheet-education.pdf
\
https://www.educative.io/answers/what-does-git-diff-head-filename-do
