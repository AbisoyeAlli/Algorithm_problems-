# Contributing to Algo-problems-
Contributions are welcome to help curate solutions to Algorithm problems asked during coding interviews. To contribute, these are the guidelines to follow:

## Found a problem?
If you find an error in any solution or a better way to optimise a solution, you can help us by submitting an issue. Even better, you can submit a Pull Request with a fix.

## SUBMISSION GUIDELINES
### Submitting an Issue:
Before you submit an issue, please search the issue tracker, maybe an issue for your problem already exists and the discussion might inform you of workarounds readily available.

### Submitting a Pull Request (PR):
Before you submit your Pull Request (PR) consider the following guidelines:

1. Search the repository for an open or closed PR that relates to your submission. You don't want to duplicate effort.

2. Be sure that an issue describes the problem you're fixing, or documents the design for the feature you'd like to add. 

3. Fork repo.

5. On your command line, clone repository
    ```
    git clone <repo-url>
    ```
6. Add remote upstream
    ```
    git remote add upstream <repo-url>
    ```
    You can check this by typing `git remote`, you should have `origin` and `upstream`

7. Run the following commands;
    `git checkout main`
    `git fetch upstream`
    `git merge upstream/main`
    `git push`

8. Create a new branch to work on
    `git checkout -b <BRANCHNAME>`

9. Make the changes you want from this branch. For new solutions, create a folder properly labelled with the problem you are solving. For example, `FizzBuzz`.

10. Add and commit your changes
    `git add <filename>` or `git add .` to add multiple files.
    `git commit -m "explicit commit message"`

11. Run the first three commands in #7 above.

12. `git checkout <YOUR-BRANCHNAME>`

13. `git rebase main`

14. Push your code
    `git push --set-upstream origin <YOUR-BRANCHNAME>`

That's it! Go ahead and click on the `Create Pull Request` button on the web.

Thank you for your contribution!