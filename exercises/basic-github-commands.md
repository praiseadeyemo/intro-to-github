
## Basic GitHub Commands Exercises

### **Exercise 1: Clone the Repository**

- **Objective:** Learn how to clone a repository from GitHub to your local machine.
- **Instructions:**

  1. Open your terminal.
  2. Run the following command (replace `your-username` with your actual GitHub username):

     ```bash
     git clone https://github.com/your-username/introduction-to-github.git
     ```
     
  3. Change into the newly cloned directory:

     ```bash
     cd introduction-to-github
     ```

---

### **Exercise 2: Create a New Branch**

- **Objective:** Understand how to create and switch to a new branch to work on a feature or change.
- **Instructions:**

  1. Create a branch called `my-feature`:

     ```bash
     git checkout -b my-feature
     ```

  2. Verify that you are now on the new branch:

     ```bash
     git branch
     ```
     
     You should see `my-feature` highlighted.

---

### **Exercise 3: Make Changes**

- **Objective:** Practice modifying an existing file or adding new content.
- **Instructions:**

  1. Open the `README.md` file in your favorite text editor.
  2. Add a new section or note (for example, you might add a heading like `## My Feature` along with some details).
  3. Alternatively, create a new file (e.g., `my-feature.txt`) and add some sample text.

---

### **Exercise 4: Stage and Commit Your Changes**

- **Objective:** Learn how to track changes and commit them locally.
- **Instructions:**

  1. Stage your changes:

     ```bash
     git add .
     ```

  2. Commit your changes with a descriptive message:

     ```bash
     git commit -m "Add feature notes in my-feature branch"
     ```

---

### **Exercise 5: Push Your Branch to GitHub**

- **Objective:** Push your local branch to the remote repository on GitHub.
- **Instructions:**

  1. Push the branch using:

     ```bash
     git push origin my-feature
     ```

  2. Confirm the push by visiting your repository on GitHub and checking the branches.

---

### **Exercise 6: Create a Pull Request (PR)**

- **Objective:** Learn how to use GitHub’s interface to create a pull request for your changes.
- **Instructions:**

  1. Go to your repository on GitHub in your web browser.
  2. You should see a prompt to create a pull request for the recently pushed branch.
  3. Click the prompt (or navigate to the "Pull Requests" tab and click "New Pull Request").
  4. Follow the on-screen instructions to open a pull request, add a title and description, and submit it.

- **Optional:** Once the pull request is reviewed and merged, you can delete your feature branch to keep the repository clean.

---

### Additional Tips (Optional)

- **Review Your Git History:**  
  After committing, you can view the commit history with:

  ```bash
  git log --oneline
  ```

- **Undoing Changes:**  
  If you make a mistake, try using commands like `git status` or `git diff` to understand the current state. You might also explore how to undo changes or reset commits.

- **Branch Management:**  
  Practice listing all branches with `git branch` and switching between them with `git checkout <branch-name>`.

---

These exercises cover the core concepts of using Git and GitHub, ensuring that newcomers gain hands-on experience with cloning, branching, editing, staging, committing, pushing, and creating pull requests. This step-by-step approach builds a strong foundation for using version control in real-world projects.








