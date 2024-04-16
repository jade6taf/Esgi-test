# Esgi-test
# Git Introduction Hands-On Lab Project

## Introduction

This hands-on lab project aims to introduce students to the basics of Git version control system, GitHub, and collaborative development practices using PHP files.

## Hands On

**Step 1**: Setting Up GitHub Accounts

- Instruct students to visit GitHub and sign up for an account if they haven't already.

**Step 2**: Understanding HTTPS vs SSH

- HTTPS: Requires users to enter their GitHub username and password each time they interact with the repository.
- SSH: Utilizes a secure key pair for authentication, offering more convenience and security.

Windows:

- Install Git Bash (Optional):
    - If you don't already have Git installed, download and install it from Git for Windows.
    - During installation, make sure to select "Git Bash Here" option in the context menu.

- Open Git Bash:
    - Right-click on the desktop or any folder and select "Git Bash Here" from the context menu.

- Generate SSH Key:
    - In the Git Bash terminal, type the following command:
        ```
        ssh-keygen -t rsa 
        ```
    - Follow the prompts:
        - Press Enter to accept the default file location.
        - You can also set a passphrase for added security.

- Locate SSH Key:
    - Your SSH keys will be stored in ~/.ssh directory (typically C:\Users\YourUsername\.ssh).

Linux & macOS:

- Open Terminal:
    - On macOS, you can find Terminal in Applications -> Utilities.
    - On most Linux distributions, you can press Ctrl + Alt + T to open the terminal.

- Generate SSH Key:
    - In the terminal, type the following command:
        ```
        ssh-keygen -t rsa
        ```

- Follow the prompts:
    - Press Enter to accept the default file location.
    - You can also set a passphrase for added security.

- Locate SSH Key:

    - Your SSH keys will be stored in ~/.ssh directory.

Step 3: Git Basics
- Git Clone: Instruct students to clone the repository to their local machine using either HTTPS or SSH, depending on their preference.
- Git Add, Git Commit, Git Push:
    - `git clone`: This command is used to create a copy of a repository from a remote server to your local machine.
    - `git add`: This command adds changes in the working directory to the staging area, preparing them to be committed.
    - `git commit`: This command records changes made to the repository. It creates a snapshot of the changes that can be reverted to or referenced in the future.
    - `git push`: This command uploads the committed changes from your local repository to a remote repository.
    - `git pull`: This command fetches changes from a remote repository and merges them into the current branch in your local repository.

## Individual commits

**Person 1:**
 - Create a GitHub Project:
    - Go to https://github.com and sign in to your account.
    - Click on the "+" icon in the top-right corner and select "New repository."
    - Fill in the repository name, description, and choose any other settings you prefer.
    - Click on "Create repository."

- Add Person 2 to the Project:
    - Go to the repository you just created.
    - Click on the "Settings" tab.
    - Select "Collaborators" from the left sidebar.
    - Type in Person 2's GitHub username and click "Add collaborator."
    - Person 2 will receive an email invitation to collaborate on the project. They need to accept it.

- Create a PHP File and Work on it:
    - Create a new PHP file in your local repository. You can name it anything you like, for example, person1.php.
    - Write PHP function to add 2 numbers in this file and save it.

- Push Changes to GitHub:
    - Open your terminal or command prompt.
    - Navigate to your local repository directory.
    - Add the changes to the staging area using git add ..
    - Commit the changes using git commit -m "Add person1.php with PHP function".
    - Push the changes to GitHub using git push.

**Person 2:**

- Clone the GitHub Project:
    - Go to the GitHub repository URL provided by Person 1.
    - Click on the "Code" button and copy the repository URL.
    - Open your terminal or command prompt.
... (64 lignes restantes)
