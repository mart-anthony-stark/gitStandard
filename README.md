# GIT STANDARD

# BRANCHING

* * *

## Naming of branch

*   **Frontend** - feat/fe/<task>
    *   Example : **feat/fe/create-login-page**
*   **Backend** \- feat/be/<task>
    *   Example : **feat/be/create-login-api**
*   **UI/UX**\- feat/ui-ux/<task>
    *   Example : **feat/ui-ux/create-login-design**
*   **Mobile** \- feat/mb/<task>
    *   Example : **feat/mb/create-login-view**
*   **Bugs -** bug/<name-of-bug>
    *   Example : **bug/login-button-not-showing**
*   **Fixes** - fix/<name-of-fix>
    *   Example : **fix/login-button**

## Create branch from master

1. Update master
2. **`git checkout -b <name-of-new-branch>`**

## Create branch from dev

1. Update dev
2. **`git checkout -b <name-of-new-branch>`**

## Create feature branch

1. Update dev
2. **`git checkout -b <name-of-feature>`**

## Create branch from a feature branch

1. **`git checkout <name-of-feature-branch>`**
2. **`git pull`**
3. **`git checkout -b <name-of-new-branch>`**

  

# UPDATE BRANCH

* * *

## MASTER

1. **`git checkout master`**
2. **`git pull`**

## DEV

1. **`git checkout dev`**
2. **`git pull`**

  

# REBASING

* * *

1. Update parent branch
    *   **NOTE: The parent branch can be** **`master`****,** **`dev`****, or a** **`feature branch`**
2. **`git checkout <name-of-branch>`**
3. **`git rebase <parent-branch>`**

# GIT FLOW

* * *

![](https://t25547353.p.clickup-attachments.com/t25547353/747a5903-4864-4ff1-96ab-dd81e6a00217/GitFlow-git-workflow-2.png)

* * *

# COMMIT MESSAGE

*   Must be less than **50 characters**.
*   Must be a sentence.
*   Must have a meaningful and descriptive message.
*   Must be straight to the point.
*   Always use the **present tense**. Don't use past or future tense.

# BEFORE COMMIT

1. Update feature branch.
2. Rebase your local branch to the update feature branch.
3. **`git push --force`**

# COMMIT CHANGES

*   Always commit files with the same changes.
*   Remove unnecessary **`console.log()`****.**
*   Don't include commented codes. Descriptive comments are allowed.
*   **Bulk commits** are not permitted.

# HOW TO COMMIT CHANGES

## COMMAND-LINE

1. Run **`git add <name-of-file>`** to add a file in your commit.
2. Keep doing **step 1** until you added all the files you want to commit.
3. Then run**`git commit -m "your message"`**to commit your changes.

  

* * *
