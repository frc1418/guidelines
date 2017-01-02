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

A rule of thumb is it should complete the sentence "If applied, this commit will <*your subject line here*>.
    
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
