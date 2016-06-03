# We Enhance IT Home Pages
This repository contains the weenhanceit.com source.

# Contributing
## First Time
1. Fork this repository
2. Make your changes
3. Push your changes up to your repository
4. Submit a pull request (PR) from your repository to the `draft` branch of this repository
4. We will review the PR, and likely make comments on it, or request changes
5. When everyone's happy with the changes, we'll merge the PR to the `draft` branch
6. When we're ready to release a new version of the weenhanceit.com web site, we merge the `draft` branch into master

## Updating Your Repository
If you've already forked the repository, but need to update your fork from `weenhanceit/weenhanceit.github.io.git`, you have to add the original respository from which you forked, as an additional remote:
```
git remote add upstream https://github.com/weenhanceit/weenhanceit.github.io.git
```
The name of the remote can be anything, but `upstream` is customary. The rest of this page assumes you named the remote `upstream`. If you named it something else, you need to change `upstream` to your remote in the subsequent examples.

When you need to update your repository with the drafts branch of `weenhanceit.github.io.git`:
```
git fetch upstream
git merge upstream/draft
```
When you need to update from the master branch:
```
git fetch upstream
git merge upstream/master
```

When you're done making your changes, submit a pull request by following the instructions for First Time, starting at step 3.
