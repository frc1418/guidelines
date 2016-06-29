# 1418 Coding Guidelines

## Code
* Use detailed comments and docstrings in all code, written in proper English. Anyone on the team with even slight knowledge of the language the code is written in, should be able to read your comments and have a good understanding of what the code does and why.
* Always follow style guides. For example, the Python [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008).

## Committing
* All commit names must be in easily legible English. You don't have to use full sentences, but the names should be clear, concise, easy to understand, and PG.

    **Good:**
    ![Good commit](images/commit2.png)
    ![Good commit](images/commit5.png)

    **Bad:**
    ![Bad commit](images/commit1.png)
    ![Bad commit](images/commit4.png)

    **Even worse:**
    ![Worse commit](images/commit3.png)
    ![Worse commit](images/commit6.png)

* Never commit directly to master. Instead:
    1. Fork the repository to your personal GitHub account.
    2. Perform your changes on that fork.
    3. Open a pull request to merge your changes to the master branch.
    4. Wait for approval from another team member.
    5. ?????
    6. Profit
* Only commit through your own GitHub account. No using dummy accounts.
* Use .gitignore files to prevent committing of useless temporary folders and files like `.DS_Store`, `.project`, `.pydevproject`, and others. [Help with `.gitignore` files](https://help.github.com/articles/ignoring-files/)

## READMEs
* All repositories should have a `README.md` file explaining their purpose, how they were used, and how to use them. (They don't need to be added until the code is publicized at the end of each season.)
* At the top of each  TODO