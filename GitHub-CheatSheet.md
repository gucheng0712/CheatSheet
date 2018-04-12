# Intro to GitHub
GitHub is a website and service that we hear geeks rave about all the time, yet a lot of people don’t really understand what it does. Want to know what all the GitHub hubbub is about? Read on to find out.

To understand GitHub, you must first have an understanding of Git. Git is an open-source version control system that was started by Linus Trovalds—the same person who created Linux. Git is similar to other version control systems—Subversion, CVS, and Mercurial to name a few.

So, Git is a version control system, but what does that mean? When developers create something (an app, for example), they make constant changes to the code, releasing new versions up to and after the first official (non-beta) release.

Version control systems keep these revisions straight, storing the modifications in a central repository. This allows developers to easily collaborate, as they can download a new version of the software, make changes, and upload the newest revision. Every developer can see these new changes, download them, and contribute.

## Setup
1.	Create your first github account in the github website: www.github.com
2.	Configuring user information used across all local repositories
```
git config --global user.name “[username]”
git config --global user.email "[email address]"

```


## In Order to Use GitHub, Understanding Some important Vocabulary is Necessary:
#### 1. Branch
>A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or master branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the master branch to publish your changes.

#### 2. Checkout
>The action of updating all or part of the working tree with a tree object or blob from the object database, and updating the index and HEAD if the whole working tree has been pointed at a new branch.

#### 3. Collaborator
>A collaborator is a person with read and write access to a repository who has been invited to contribute by the repository owner.

#### 4. Fetch
>Fetching refers to getting the latest changes from an online repository without merging them in. Once these changes are fetched you can compare them to your local branches (the code residing on your local machine).

#### 5. Merge
>Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a pull request (which can be thought of as a request to merge), or via the command line. A merge can be done automatically via a pull request via the GitHub web interface if there are no conflicting changes, or can always be done via the command line. For more information, see "Merging a pull request.

#### 6. Pull
>Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.

#### 7. Pull Request
>Pull requests are proposed changes to a repository submitted by a user and accepted or rejected by a repository's collaborators. Like issues, pull requests each have their own discussion forum. For more information, see "About pull requests."

#### 8. Push
>Pushing refers to sending your committed changes to a remote repository, such as a repository hosted on GitHub. For instance, if you change something locally, you'd want to then push those changes so that others may access them.

#### 9. Remote
>This is the version of something that is hosted on a server, most likely GitHub. It can be connected to local clones so that changes can be synced.

## The Following Table has some common commands for GitHub

|Command  | Function|
|------------ | -------------|
|`git init` | Initialize an existing directory as a git repository|
|`git clone [url]` | Clone an entire repository from the url|
|`git status` | Modified files in working directory, staged for your next commit(stage).|
|`git add [file]` | Add a file as it looks now to your next commit (stage). |
|`git add .` | Add everything in this location to your next commit|
|`git reset [file]` | Unstage a file while retaining the changes in working directory|
|`git diff` | Difference of what is changed but not staged|
|`git diff --staged` | Difference of what is staged but not yet commited|
|`git commit -m "[descriptive message]"` | Commit your staged content |
|`git branch` | List your branches. a `*` will appear next to the currently active branch|
|`git branch [branch-name]` | Create a new branch at the current commit|
|`git checkout` | Switch to another branch and check it out into your working directory|
|`git merge [branch]` | Merge the specified branch’s history into the current one|
|`git log` | Show all commits in the current branch’s history|
|`git rm [file]` | Delete the file from project and stage the removal for commit __(be careful to use)__|
|`git mv [file_from] [file_to]` | Move file to another location |
