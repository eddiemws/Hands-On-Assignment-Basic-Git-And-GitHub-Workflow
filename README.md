Hands-On Assignment: Basic Git And GitHub Workflow
Objective:

The objective of this assignment is to familiarize students with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.


Requirements:

- A GitHub account (create one if you don't have it already).

- Git installed on your local machine.

- A code editor of your choice (e.g., Visual Studio Code, Sublime Text).




Task 1: Repository Setup

1. GitHub Repository Creation:

  - Log in to your GitHub account.

  - Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").

  - Initialize it with a README file.



Task 2: Local Setup

2. Local Folder Setup:

  - Create a new folder on your local machine (e.g., "PLPBasicGitAssignment").

  - Open a terminal or command prompt and navigate to the created folder.



3. Git Initialization:

  - Initialize a new Git repository in your local folder.



4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin <repository-url>

   ```

   Replace `<repository-url>` with the actual URL of your GitHub repository.



Task 3: Making Changes

5. Create a File:

  - Inside your local folder, create a new text file (e.g., `hello.txt`).

  - Add a simple text message (e.g., "Hello, Git!").



6. Committing Changes:

  - Stage the changes.

   ```bash

   git add hello.txt

   ```

  - Commit the changes.

   ```bash

   git commit -m "Add hello.txt with a greeting"

   ```



Task 4: Pushing to GitHub

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.

   ```bash

   git push -u origin main

   ```



Task 5: Verification

8. Verify on GitHub:

  - Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.



Submission:

- Ensure all changes are pushed to your GitHub repository.

- Share the link to your GitHub repository with the instructor or submit it as per the class instructions.



Additional Tips:

- Document the steps and commands used in a text file or in the README of your repository.

- If you encounter issues, refer to the GitHub documentation or seek assistance from peers or the instructor.



This assignment is a basic introduction to the Git and GitHub workflow, emphasizing repository creation, local setup, making changes, committing, and pushing to GitHub.
