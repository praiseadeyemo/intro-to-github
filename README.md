# Introduction to GitHub

Welcome to the Introduction to GitHub repository! This repository is designed to help you get started with GitHub by walking you through basic commands and a simple task to practice your skills.

## Contents

- [Basic GitHub Commands Exercise](exercises/basic-github-commands.md)
- [Simple GitHub Task](exercises/simple-github-task.md)

## How to Get Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/intro-to-github.git
   cd introduction-to-github
Below is an example of how you can set up your GitHub repository for an introduction to GitHub. You can create a new repository (for example, named `introduction-to-github`) and include the following files and content.

---

### 1. Repository Structure

```
introduction-to-github/
├── README.md
└── exercises/
    ├── basic-github-commands.md
    └── simple-github-task.md
```

---

### 2. File Contents

#### **README.md**

```markdown
# Introduction to GitHub

Welcome to the Introduction to GitHub repository! This repository is designed to help you get started with GitHub by walking you through basic commands and a simple task to practice your skills.

## Contents

- [Basic GitHub Commands Exercise](exercises/basic-github-commands.md)
- [Simple GitHub Task](exercises/simple-github-task.md)

## How to Get Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/introduction-to-github.git
   cd introduction-to-github
   ```

2. **Follow the Exercises:**
   - Open the `exercises/basic-github-commands.md` file and follow the instructions to practice common Git commands.
   - Open the `exercises/simple-github-task.md` file to complete a simple GitHub task.

3. **Need Help?**
   If you have any questions or issues, feel free to open an issue in this repository.

Happy learning!
```

---

#### **exercises/basic-github-commands.md**

```markdown
# Basic GitHub Commands Exercise

In this exercise, you'll practice some fundamental Git and GitHub commands.

## Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/introduction-to-github.git
   cd introduction-to-github
   ```

2. **Create a New Branch:**

   Create a branch called `my-feature` where you will make your changes:

   ```bash
   git checkout -b my-feature
   ```

3. **Make Changes:**

   Edit the `README.md` file (or create a new file) to add your notes or any content.

4. **Stage and Commit Your Changes:**

   ```bash
   git add .
   git commit -m "Add my changes in my-feature branch"
   ```

5. **Push Your Branch to GitHub:**

   ```bash
   git push origin my-feature
   ```

6. **Create a Pull Request:**

   - Go to your repository on GitHub.
   - You should see a prompt to create a Pull Request (PR) for your newly pushed branch.
   - Click the prompt and follow the instructions to open a PR.

Once your PR is merged, your changes will be part of the main branch.
```

---

#### **exercises/simple-github-task.md**

```markdown
# Simple GitHub Task

This task will help you practice creating a branch, adding a new file, and making a pull request.

## Task: Contribute Your Own Message

1. **Create a New Branch:**

   Create a branch called `contribute-message`:

   ```bash
   git checkout -b contribute-message
   ```

2. **Add a New File:**

   Create a file named `CONTRIBUTION.md` in the repository root with the following content:

   ```markdown
   # Contribution

   Hello! I am contributing to this repository as part of the Introduction to GitHub exercise.
   ```

3. **Stage and Commit Your Changes:**

   ```bash
   git add CONTRIBUTION.md
   git commit -m "Add CONTRIBUTION.md with a welcome message"
   ```

4. **Push Your Branch to GitHub:**

   ```bash
   git push origin contribute-message
   ```

5. **Open a Pull Request:**

   - Go to your repository on GitHub.
   - Open a Pull Request (PR) to merge your `contribute-message` branch into the `main` branch.
   - Follow the prompts to create the PR.

6. **Optional Cleanup:**

   After your PR is merged, you can delete the branch if you wish.
```

---

### 3. How to Create This Repository on GitHub

1. **Create the Repository on GitHub:**
   - Go to [GitHub](https://github.com) and click the **New repository** button.
   - Name your repository (e.g., `introduction-to-github`), add a description, and choose whether to make it public or private.
   - **Do not** initialize with a README if you plan to add one locally (or initialize it and adjust your local repository accordingly).

2. **Clone and Add Files Locally:**
   - Clone the repository:

     ```bash
     git clone https://github.com/your-username/introduction-to-github.git
     cd introduction-to-github
     ```

   - Create the file structure as shown above.
   - Add the files with the content provided.
   - Commit and push your changes:

     ```bash
     git add .
     git commit -m "Initial commit with README and exercises"
     git push origin main
     ```

3. **Verify on GitHub:**
   - Open your repository in a web browser to verify that the files have been added correctly.

---

This setup should provide a solid starting point for anyone new to GitHub. It includes a clear introduction, practical exercises to learn the basic Git commands, and a task that mimics real-world contribution workflows. Happy coding and learning!
