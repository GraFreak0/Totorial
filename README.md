# Totorial
This is a repository for a training 

# How to Create a Repository on GitHub

Follow these steps to create a new repository on GitHub:

## Step 1: Sign In to GitHub

1. Open your web browser and go to [GitHub](https://github.com/).
2. Click on the **Sign In** button in the upper right corner.
3. Enter your username and password to log in.

## Step 2: Create a New Repository

1. After signing in, click on the **+** icon in the upper right corner next to your profile picture.
2. Select **New repository** from the dropdown menu.

## Step 3: Configure Your New Repository

1. **Repository Name**: Enter a name for your repository. Make sure the name is unique and relevant to your project.
2. **Description** (optional): Write a short description of your repository.
3. **Public or Private**: Choose whether you want your repository to be public or private.
    - **Public**: Anyone on the internet can see this repository.
    - **Private**: You choose who can see and commit to this repository.
4. **Initialize this repository with a README** (optional but recommended): Check this box to include a README file.

## Step 4: Create the Repository

1. Once you have filled in the necessary information, click on the **Create repository** button at the bottom of the page.

## Step 5: Adding Files to Your Repository
### Initializing and  Using Git on Your Local Machine

1. Create a Folder on any location on your local machine.
2. Right-click and select "Open in Terminal" from the options to open the location using command prompt.
3. Initialize git (On command prompt)
   ```bash
    git init
   ```
4. Add the remote online Github repository to the Local folder.
   ```
   git remote add origin <repository_url>
   ```
6. Pull the existing records and files from the repository.
   ```
   git pull origin main --allow-unrelated-histories
   ```
8. Change your git branch to the `main` branch.
   ```
   git checkout main
   ```
10. Delete the `master` branch (was automatically created when you initialized git locally).
    ```
    git branch -D master
    ```
12. Upload/Copy whatever files you want to push into the folder on your local machine.
14. Check the git status
    ```
    git status
    ```
15. Add the files to the commit chain for pushing to the online repository
    ```
    git add filename
    ```
17. Commit your changes:
    ```bash
    git commit -m "Your commit message here"
    ```
18. Push your changes to GitHub:
    ```bash
    git push origin main
    ```

## Conclusion

Congratulations! You have successfully created a new repository on GitHub and added files to it. You can now continue to manage your repository, collaborate with others, and track your project's progress.

For more detailed information, visit the [GitHub Docs](https://docs.github.com/).

## Video Guide
You can also checkout a video demonstration on YouTube [YouTube](https://youtu.be/QTRFNgmJQaA).
