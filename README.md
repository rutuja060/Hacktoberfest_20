# Hacktoberfest_20

# Hacktoberfest_20

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

### This repository aims to help code beginners with their first successful pull request and open source contribution. :partying_face:

:star: Feel free to use this project to make your first contribution to an open-source project on GitHub. Practice making your first pull request to a public repository before doing the real thing!

:star: Make sure to grab some cool swags during Hacktoberfest by getting involved in the open-source community.

### This repository is open to all members of the GitHub community. Any member can contribute to this project! :grin:

:point_right: Repo Link : [https://github.com/manan-bedi2908/Hacktoberfest_20](https://github.com/manan-bedi2908/Hacktoberfest_20)

## What is Hacktoberfest? :thinking:
A month-long celebration from October 1st to October 31st presented by [Digital Ocean](https://hacktoberfest.digitalocean.com/) and [DEV Community](https://dev.to/) collaborated with [GitHub](https://github.com/blog/2433-celebrate-open-source-this-october-with-hacktoberfest) to get people involved in [Open Source](https://github.com/open-source). Create your very first pull request to any public repository on GitHub and contribute to the open-source developer community.

[https://hacktoberfest.digitalocean.com/](https://hacktoberfest.digitalocean.com/)


## Rules :fire:
To qualify for the __official limited edition Hacktoberfest shirt__, you must register [here](https://hacktoberfest.digitalocean.com/) and make four Pull Requests (PRs) between October 1-31, 2020 (in any time zone). PRs can be made to any public repo on GitHub, having title to the repo as hacktoberfest. This year, the __first 70,000__ participants who complete the challenge will earn a T-shirt.

## Feel Free to contribute to any code in the repository

### 1. Exploratory Data Analysis - Explore any dataset and you can add it here
### 2. Python for Data Science - Feel free to push any code that is useful for data science (NumPy, Pandas, Scikit-Learn)
### 3. Algorithm - Push any code of the algorithm related to ML, Basic DSA, Greedy Algos, Big Data algos, etc.


## Steps to follow :scroll:

### 0. Star The Repo :star2:

Star the repo by pressing the topmost-right button to start your wonderful journey.


### 1. Fork it :fork_and_knife:


### 2. Clone it :busts_in_silhouette:

`NOTE: commands are to be executed on Linux, Mac, and Windows`

You need to clone (download) it to local machine using

```sh
$ git clone https://github.com/Your_Username/Hacktoberfest_2020.git
```

> This makes a local copy of the repository in your machine.

Once you have cloned the `Hacktoberfest_2020` repository in Github, move to that folder first using change directory command on Linux, Mac, and Windows
```sh
# This will change directory to a folder Hacktoberfest_2020
$ cd Hacktoberfest_2020
```

Move to this folder for all other commands.

### 3. Set it up :arrow_up:

Run the following commands to see that *your local copy* has a reference to *your forked remote repository* in Github :octocat:

```sh
$ git remote -v
origin  https://github.com/Your_Username/Hacktoberfest_2020.git (fetch)
origin  https://github.com/Your_Username/Hacktoberfest_2020.git (push)
```

Now, let's add a reference to the original [Hacktoberfest_2020](https://github.com/manan-bedi2908/Hacktoberfest_20/) repository using

```sh
$ git remote add upstream https://github.com/manan-bedi2908/Hacktoberfest_20.git
```

> This adds a new remote named ***upstream***.

See the changes using

```sh
$ git remote -v
origin    https://github.com/Your_Username/Hacktoberfest_2020.git (fetch)
origin    https://github.com/Your_Username/Hacktoberfest_2020.git (push)
upstream  https://github.com/Remote_Username/Hacktoberfest_2020.git (fetch)
upstream  https://github.com/Remote_Username/Hacktoberfest_2020.git (push)
```
`In your case, you will see`
```sh
$ git remote -V
origin    https://github.com/Your_Username/Hacktoberfest_2020.git (fetch)
origin    https://github.com/Your_Username/Hacktoberfest_2020.git (push)
upstream  https://github.com/manan-bedi2908/Hacktoberfest_20.git (fetch)
upstream  https://github.com/manan-bedi2908/Hacktoberfest_20.git (push)
```

### 4. Sync it :recycle:

Always keep your local copy of the repository updated with the original repository.
Before making any changes and/or in an appropriate interval, run the following commands *carefully* to update your local repository.

```sh
# Fetch all remote repositories and delete any deleted remote branches
$ git fetch --all --prune

# Switch to `master` branch
$ git checkout main

# Reset local `master` branch to match the `upstream` repository's `master` branch
$ git reset --hard upstream/main

# Push changes to your forked `Hacktoberfest_2020` repo
$ git push -u origin main
```

### 5. Ready Steady Go... :turtle: :rabbit2:

Once you have completed these steps, you are ready to start contributing by checking our `Good First Issue` Issues and creating [pull requests](https://github.com/manan-bedi2908/Hacktoberfest_20/pulls).

### 6. Create a new branch :bangbang:

Whenever you are going to contribute. Please create a separate branch using command and keep your `main` branch clean (i.e. synced with remote branch).

```sh
# It will create a new branch with name Branch_Name and switch to branch Folder_Name
$ git checkout -b BranchName
```

Create a separate branch for contribution and try to use the same name of the branch as of folder.

To switch to the desired branch

```sh
# To switch from one folder to other
$ git checkout BranchName
```

To add the changes to the branch. Use

```sh
# To add all files to branch Folder_Name
$ git add .
```

Type in a message relevant for the code reviewer using

```sh
# This message get associated with all files you have changed
$ git commit -m 'relevant message'
```

Now, Push your awesome work to your remote repository using

```sh
# To push your work to your remote repository
$ git push -u origin BranchName
```

Finally, go to your repository in the browser and click on `compare and pull requests`.
Then add a title and description to your pull request that explains your precious effort.

## Awesome contributors :star_struck:
<a href="https://github.com/manan-bedi2908/Hacktoberfest_20/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=manan-bedi2908/Hacktoberfest_20" />
</a>

Made with [contributors-img](https://contributors-img.web.app).

## Help Contributing Guides :crown:

Please discuss it with us first by creating a new issue.

:tada: :confetti_ball: :smiley: _**Happy Contributing**_ :smiley: :confetti_ball: :tada:

