# GitHub Repository Assignment

**Student ID:** 22263520

## A. Creating the Repository

1. I signed in to the GitHub platform using my Google email.
2. I clicked the hamburger icon at the top-left corner of the window and selected **All Repositories**.
3. I clicked the **New Repository** button to open the repository creation interface.
4. I entered my repository name (**DCIT-323-GIT-GITHUB-ASSIGNMENT**), set the visibility to **Public**, and confirmed the creation.

## B. Cloning the Repository

1. From Windows PowerShell, I used the `cd` command to navigate to the folder where I wanted to clone my repository.
2. I then used the following `git clone` command to clone the repository to the specified location:

   ```bash
   git clone https://github.com/Yaotib/DCIT-323-GIT-GITHUB-ASSIGNMENT.git

3. I opened the cloned folder in Visual Studio Code and added a README file.

## C. Pushing to GitHub

1. I used the `git init` command to initialize Git.

2. Then I used `git add .` to track all the new folders and files I created.

3. Then I used `git status` to check the tracked folders and files.

4. Then I used the following command to create a snapshot of my first change:

   ```bash
   git commit -m "First commit_dcit 323 assignment"

5. Finally, I used the following command to push my changes to GitHub:

    ```bash
    git push origin main