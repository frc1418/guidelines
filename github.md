# 1418 Github Guildlines

## Setting up your repo
Start off by creating a fork of the repo you will be working on. Don't clone it directly. This allows you to create *Pull Requests*, which are ways of allowing your code to be peer reviewed before merging it with the master branch. 

  * Fork and clone the team repo

You can now push code to your branch, but in order to keep up with the team master branch, you'll need to add a *remote* that links to the team master branch. To add a remote

`git remote add upstream git://github.com/frc1418/repo`

Once you're ready to pull changes from the team master branch:

```
git fetch upstream
git checkout master
git merge upstream/master
```

Make sure you switch back to your feature branch before continuing programming.

## Commiting
All commit names must be coherent explanations of the commit, written in legible English, **in the imperative**. The imperative is the verbal form used when giving a command. For example, do not write
	
    `Added TwoBallHot autonomous`
 
Instead, write
 	
    `Add TwoBallHot autonomous`

A rule of thumb is it should complete the sentence "If applied, this commit will <*your subject line here*>."
    
You don't have to use full sentences, but the names should be clear, concise, and PG.

**Good:**
![Good commit](images/commit2.png)
![Good commit](images/commit5.png)

**Bad:**
![Bad commit](images/commit3.png)
![Bad commit](images/commit6.png)

**Even worse:**
![Worse commit](images/commit1.png)
![Worse commit](images/commit4.png)

* Never commit directly to master. Always commit to your branch

    
* Only commit through your own GitHub account. No using dummy accounts.
    * Relatedly, your GitHub account should have your real name on it so we can tell who's who. (You can use whatever you want for your username, but your real name should be used on the _Name_ portion of your account page.)
* Use `.gitignore` files to prevent committing of useless temporary folders and files like `.DS_Store`, `.project`, `.pydevproject`, `node_modules`, and others. [Help with .gitignore files](https://help.github.com/articles/ignoring-files)

##Rebasing
Sometimes when you make a pull request there a some changes that need to be made to make the feature complete. This is normal, as you may not always think of everything from the get go, but it does create a problem. Every time you commit and update the feature it will be added to the commit history. This is generally not what you want. For example, let's say you create `drive.py`, but accidently leave out an important line of code. You could have two commits: `Add drive.py` and `Add line of code`, but it would make sense and look better for it to all be under `Add drive.py`. To merge these, we use `git rebase`

Rebasing is a way of rewriting git history. There are some more advanced things you can do with it but for now we're going to talk about squashing commits. 

Once you have commited your code *but not pushed*, run `git rebase -i HEAD~n` where n is the number of commits ago you want to squash. Generally, n will be 2, because you'll make the first commit, realize you left something, make another commit, and squash. But let's say you commit, remember another thing, and commit again. Now your history looks like

```
$ git log --pretty=oneline
a931ac7c808e2471b22b5bd20f0cad046b1c5d0d addition 2
b76d157d507e819d7511132bdb5a80dd421d854f addition 1
df239176e1a2ffac927d8b496ea00d5488481db5 original
```
We want to squash the last 3 together, so we run `git rebase -i HEAD~3` and you get this:

```
pick df23917 original
pick b76d157 addition 1
pick a931ac7 addition 2

# Rebase df23917..a931ac7 onto df23917
#
# Commands:
#  p, pick = use commit
#  r, reword = use commit, but edit the commit message
#  e, edit = use commit, but stop for amending
#  s, squash = use commit, but meld into previous commit
#  f, fixup = like "squash", but discard this commit's log message
#
# If you remove a line here THAT COMMIT WILL BE LOST.
# However, if you remove everything, the rebase will be aborted.
#
``` 

This is the interactive rebaser. At the top, you'll see the log of commits you're working with. To the left of each commit will be `pick`. To rebase, find the commit you want to be the one and only commit. Leave this as `pick`. Change the other `pick`s to `s` or `squash` (the both do the same thing). It should look like:

```
pick df23917 original
s b76d157 addition 1
s a931ac7 addition 2


# Rebase df23917..a931ac7 onto df23917
#
# Commands:
#  p, pick = use commit
#  r, reword = use commit, but edit the commit message
#  e, edit = use commit, but stop for amending
#  s, squash = use commit, but meld into previous commit
#  f, fixup = like "squash", but discard this commit's log message
#
# If you remove a line here THAT COMMIT WILL BE LOST.
# However, if you remove everything, the rebase will be aborted.
#
``` 
Once you do that, save and exit. You will be greeted by another screen. 

```
# This is a combination of 3 commits.
# The first commit's message is:

original

# This is the 2nd commit message:

addition 1

# This is the 3rd commit message:

addition 2
```

Now you have a choice of what you want the commit message to look like. You can comment out the new commit messages and only have one, or keep all 3. It's probably not necessary to keep all three, so add a `#` before `additon 1` and `addition 2`.

Now you're ready to push. This will be a special push because we need to force it, so we will use the `+` operator. 

`git push origin +branch`

And now your PR will show 1 commit, with all the changes