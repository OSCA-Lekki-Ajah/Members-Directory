# Contributing to [Members-Directory]
We would love for you to contribute to Members-Directory to help curate a list of all members within the chapter. As a contributor, here are the guidelines we would like you to follow:

## Code of Conduct
Please read and follow our [code of conduct](#)

## Question or Problem?
Do not open issues for general support questions as we want to keep GitHub issues for bug reports and feature requests. You've got much better chances of getting your question answered on [Discord Channel]() or google.

## Found a bug?
If you find a bug in the source code, you can help us by submitting an issue to our GitHub Repository. Even better, you can submit a Pull Request with a fix.

## Missing feature?
You can request a new feature by submitting an issue to our GitHub Repository. If you would like to implement a new feature, please submit an issue with a proposal for your work first, to be sure that we can use it. Please consider what kind of change it is:

- For a Major Feature, first open an issue and outline your proposal so that it can be discussed. This will also allow us to better coordinate our efforts, prevent duplication of work, and help you to craft the change so that it is successfully accepted into the project.

- Small Features can be crafted and directly submitted as a Pull Request.

## SUBMISSION GUIDELINES
### Submitting an Issue:
Before you submit an issue, please search the issue tracker, maybe an issue for your problem already exists and the discussion might inform you of workarounds readily available.

### Submitting a Pull Request (PR):
Before you submit your Pull Request (PR) consider the following guidelines:

1. Search the repository for an open or closed PR that relates to your submission. You don't want to duplicate effort.

2. Be sure that an issue describes the problem you're fixing, or documents the design for the feature you'd like to add. 

3. Make sure you sign with the primary email address of the Github identity that has been granted access to the team repository.

4. Fork repo.

5. Make your changes in a new git branch:
   ```
   git checkout -b my-branch
   ```
    
6. Create your patch, including appropriate test cases.

7. Run tests and ensure that all tests pass.

8. Commit your changes using a descriptive commit message 
    ```
    git commit -a
    ```
    Note: the optional commit -a command line option will automatically "add" and "rm" edited files.

9. Push your branch to GitHub:
    ```
    git push origin my-fix-branch
    ```

10. In GitHub, send a pull request to the appropriate branch.

11. If we suggest changes, make the required updates.

13. Rebase your branch and force push to your GitHub repository (this will update your Pull Request):
    ```
    git rebase master -i
    git push -f
    ```

That's it! Thank you for your contribution!

After your pull request is merged, you can safely delete your branch and pull the changes from the main (upstream) repository:

1. Delete the remote branch on GitHub either through the GitHub web UI or your local shell as follows:
    ```
    git push origin --delete my-fix-branch
    ```

2. Check out the master branch:
   ```
   git checkout master -f
   ```

3. Delete the local branch:
   ```
   git branch -D my-fix-branch
   ```

4. Update your master with the latest upstream version:
   ```
   git pull --ff upstream master
   ```
