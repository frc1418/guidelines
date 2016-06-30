# 1418 Programming Guidelines
This list contains general rules and regulations to be applied for all code written on this organization for Team 1418.

You must follow these rules unless you have a very good reason. If you have a general disagreement with these guidelines, please make a pull request and your proposed changes will be discussed.

## Code
* All competition repositories should be named [year]-[purpose]. For example, 2016-robot for the 2016 robot code, or 2015-UI for the 2015 User Interface.
    * Non-competitive repositories don't need to follow this standard. For example, if you create a tool that isn't bound to any one competition, you can name it anything you see fit, like [pybasictraining](https://github.com/frc1418/pybasictraining) or [RobotRecorder](https://github.com/frc1418/RobotRecorder).
* Use detailed comments and docstrings in all code, written in proper English. Anyone on the team with even mediocre knowledge of the language the code is written in should be able to read your comments and have a good understanding of what the code does and why.
* Always follow style guides and best practices. For example, when writing Python code, follow the [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008).
    * For web languages (HTML/CSS/JS), follow the [Viget FED Best Practices](https://github.com/greypants/FED-docs/blob/master/Best-Practices.md).
* Before being publicized at the end of the season, all repositories should have a `README.md` markdown file explaining their purpose, how the code was used during the season, and how those interested can make use of the code themselves.
    * At the top of each README, a short title should be present saying what the repository is. For example, "2016 Robot Code" or "2015 User Interface".
    * Underneath the title, a set of links should be present linking to the other main repositories used that season.
    * At the end of the README should be a list of authors who contributed to the repository.
    * An example of a good README can be found [here](https://github.com/frc1418/2016-robot/blob/master/README.md).

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
    * Perform your changes on that fork.
    * Open a pull request to merge your changes to the master branch.
    * Wait for the pull request to be merged by another team member. Merging your own pull request is bad practice.
* Only commit through your own GitHub account. No using dummy accounts.
    * Relatedly, your GitHub account should have your real name on it. (You can use whatever you want for your username, but your real name should be used on the _Name_ portion of your account page.)
* Use `.gitignore` files to prevent committing of useless temporary folders and files like `.DS_Store`, `.project`, `.pydevproject`, `node_modules`, and others. [Help with `.gitignore` files](https://help.github.com/articles/ignoring-files)
