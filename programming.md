# 1418 Programming Guidelines
This list contains general rules and regulations to be applied for all code written on this organization for Team 1418. Please don't write team code that violates these regulations without good reason. If you have write access to team repositories, please don't merge pull requests that break these rules.

## Code
* All code (and pull request discussion, etc.) must be PG. All code is eventually public and looked at by many other teams. Showing off a repository full of cuss words is bad PR and should be avoided.
* All competition repositories should be named [year]-[purpose]. For example, "2016-robot" for the 2016 robot code, or "2015-UI" for the 2015 User Interface.
    * Non-competitive repositories don't need to follow this standard. For example, if you create a tool that isn't bound to any one competition, you can name it anything you see fit, like [pybasictraining](https://github.com/frc1418/pybasictraining), [Victiscout](https://github.com/frc1418/Victiscout), or [RobotRecorder](https://github.com/frc1418/RobotRecorder).
* Use detailed comments in all code, written in proper English. Anyone on the team with even mediocre knowledge of the language the code is written in should be able to read your comments and have a good understanding of what the code does and why.
    * Furthermore, write detailed TODOs wherever you think of something that could be improved (if you aren't able to improve it at the moment.) For example, in JavaScript:

            // TODO: Make button move better

        Or, in Python:

            # TODO: Test this autonomous at a slower speed.

* Always follow style guides and best practices. For example, when writing Python code, follow the [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008).
    * For web languages (HTML/CSS/JS), follow the [Viget FED Best Practices](https://github.com/greypants/FED-docs/blob/master/Best-Practices.md).
* Before being publicized at the end of the season, all repositories should have a `README.md` markdown file explaining their purpose, how the code was used during the season, and how those interested can make use of the code themselves.
    * At the top of each README, a short title should be present saying what the repository is. For example, "2016 Robot Code" or "2015 User Interface".
    * Underneath the title, a set of links should be present linking to the other main repositories used that season.
    * At the end of the README should be a list of authors who contributed to the repository.
    * An example of a good README can be found [here](https://github.com/frc1418/2016-robot/blob/master/README.md).
* Each public repository must additionally include a `LICENSE` file explaining how others are allowed to use our team code. You can use [this website](http://choosealicense.com) if you're not sure which license you should include on the repository. When in doubt, use MIT.

## Committing
* All commit names must be coherent explanations of the commit, written in legible English. You don't have to use full sentences, but the names should be clear, concise, and PG.

    **Good:**
    ![Good commit](images/commit2.png)
    ![Good commit](images/commit5.png)

    **Bad:**
    ![Bad commit](images/commit3.png)
    ![Bad commit](images/commit6.png)

    **Even worse:**
    ![Worse commit](images/commit1.png)
    ![Worse commit](images/commit4.png)

* Never commit directly to origin (the repository owned by the team GitHub organization). Instead:
    * Fork the repository to your personal GitHub account.
    * Make a branch on that fork and name it after whatever you're changing. For example, `add-autonomous` or `better-buttons`.
    * Perform your changes on that branch.
    * Open a pull request to merge your changes to the master branch of the main repository.
    * Wait for the pull request to be merged by another team member. Merging your own pull request is bad practice, but you may do it if it's extremely urgent.
* Only commit through your own GitHub account. No using dummy accounts.
    * Relatedly, your GitHub account should have your real name on it. (You can use whatever you want for your username, but your real name should be used on the _Name_ portion of your account page.)
* Use `.gitignore` files to prevent committing of useless temporary folders and files like `.DS_Store`, `.project`, `.pydevproject`, `node_modules`, and others. [Help with `.gitignore` files](https://help.github.com/articles/ignoring-files)

## Miscellaneous
* Save a good reason not to, please use the portrait of yourself from [the Team Profiles page](http://1418.team) on our website as your GitHub user picture. You'll need to scale it up to 512x512 with [GIMP](http://www.gimp.org/downloads) or another photo editing tool.