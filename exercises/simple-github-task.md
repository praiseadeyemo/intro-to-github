

```markdown
# Simple GitHub Task

In this exercise, you'll practice the typical workflow of contributing to a repository. You will:

- Create a new branch.
- Add a new file with your contribution message.
- Stage and commit your changes.
- Push the branch to GitHub.
- Open a pull request to merge your changes.

Follow the steps below:

---

## Step 1: Create a New Branch

1. Open your terminal and navigate to the local copy of your repository.
2. Create a new branch named `contribute-message`:

   ```bash
   git checkout -b contribute-message
   ```

3. Verify that you have switched to the new branch by running:

   ```bash
   git branch
   ```

   You should see `contribute-message` marked as the current branch.

---

## Step 2: Add a New File

1. In the repository root, create a new file called `CONTRIBUTION.md`.
2. Open `CONTRIBUTION.md` in your favorite text editor and add the following content (feel free to personalize it):

   ```markdown
   # Contribution

   Hello! I am contributing to this repository as part of the Introduction to GitHub exercise.
   ```

3. Save the file.

---

## Step 3: Stage and Commit Your Changes

1. Stage the new file using Git:

   ```bash
   git add CONTRIBUTION.md
   ```

2. Commit your changes with a clear and descriptive message:

   ```bash
   git commit -m "Add CONTRIBUTION.md with a contribution message"
   ```

---

## Step 4: Push Your Branch to GitHub

1. Push your new branch to the remote repository:

   ```bash
   git push origin contribute-message
   ```

2. After pushing, you can visit your repository on GitHub to see that your branch now exists.

---

## Step 5: Create a Pull Request (PR)

1. Go to your repository on GitHub in your web browser.
2. You should see a prompt to compare & create a pull request for the recently pushed branch. Click that prompt.  
   _Alternatively:_
   - Click on the **Pull requests** tab.
   - Click the **New pull request** button.
   - Select your `contribute-message` branch as the source.
3. Fill in the PR title and description, then submit your pull request.
4. If desired, request a review or merge the PR (if you have permission) after ensuring everything looks good.

---

## Optional: Clean Up After Merging

- Once your pull request is merged into the main branch, you can delete the `contribute-message` branch to keep the repository tidy. GitHub provides an option to delete the branch right from the pull request page.

---

## Recap

In this task, you practiced:
- Creating and switching to a new branch.
- Adding and editing a file.
- Staging, committing, and pushing your changes.
- Opening a pull request on GitHub.

Congratulations on completing your simple GitHub task!
```

---
