# Code review process

- Clone the repository.
- Create a new branch. Every new feature should have different branch.
   
   **Note:** Before you create a branch, it's a good idea to adhere to a naming convention. For example, if your branch is for working on a new feature, you might use feature/<branch-name>. For a bug fix, you could use bugfix/<bug-number>.
   
   To create a new branch and switch to it at the same time, you can run the git checkout command with the -b switch:
   ```
   $ git checkout -b BRANCH_NAME
   Switched to a new branch "BRANCH_NAME"
   ```
   This is shorthand for:
   ```
   $ git branch BRANCH_NAME
   $ git checkout BRANCH_NAME
   ```
- Make changes.
- Test your changes.
- Commit changes and push to the branch. Make sure that each commit does not have more than 100 lines of change.
- Create a merge/pull request (Follow below steps)
   - Copy and paste the [checklist](https://raw.githubusercontent.com/tensult/coding-guidelines/master/code-review-checklist.txt) content in [stackedit](https://stackedit.io/app#) and tick checkboxes on the right side. Once you finish then copy the content from left side and paste in the merge/pull request message. Code authors should check their part in        the checklist. (If you are not checking any checkbox give reasons for that)
![Screenshot at Jan 02 18-40-15-edited](https://user-images.githubusercontent.com/30007458/71668578-6f5a8d00-2d8f-11ea-8a9c-4e9e9959a856.png)

- Require code reviews before merging the changes (This step is for Code Reviewer. Follow below steps)
   - Review the code changes.
   - Edit the merge/pull request message and the copy, paste the checklist content in [stackedit](https://stackedit.io/app#). After that, tick checkboxes for Code Reviewer only. After finishing, copy the content from left side and paste in the pull request message and save it. (If you are not checking any checkbox give reasons for that)
   - Approve the pull request.
