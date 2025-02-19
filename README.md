# A02 GitHub, Git, and VScode Tutorial

Welcome to the **A02** repository! This guide will walk you through the process of using **GIT**, **GitHub**, and **VScode** for version control and collaboration. Follow the instructions step-by-step to efficiently manage your code and collaborate with others.

---

### PART 1: Directions on Using Git, Github, and VScode.

*Step 1: Create a GitHub Account*
1. Go to [GitHub's sign-up page](https://github.com/signup).
2. Create an account by filling in your username, email, and password.
3. Verify your email address by following the instructions sent to your email.

*Step 3: Install VScode*
1. Go to [VScode's download page](https://visualstudio.com/Download).
2. Download the installer from your OS
3. Run the installer and follow the on-screen instructions.

*Step 4: Install GIT*
1. Visit [GIT's official website](https://git-scm.com/downloads/win).
2. Download and install GIT for your operating system.
3. Once the installer is downloaded, double-click the .exe file to start the installation process.
4. Follow the installation wizard with the default settings unless you have specific preferences. Here are the important steps:
5. Select Components: Leave all the default components selected (including Git Bash).
6. Adjust the default editor: Choose your preferred text editor, or leave the default (VScode is much preferred for this tutorial).
7. Adjust your PATH environment: Choose Git from the command line and also from 3rd-party software (This will allows you to use GIT in Git Bash as well as in other applications like VScode for example).


*Step 6: GIT configuration*
1. Set your username and email with the following command here below in Git Bash:
2. `git config --global user.name "yourUCID"`
3. `git config --global user.email yourUCID@example.com`

Once you have all three setup manually, it’s time to start using it fully.

### PART 2: Basic Git Commands.

*Step 1: Create a New Repository on GitHub*
1. Login to your newly created Github account
2. Click the "+" icon at the top-right and select **New repository**.
3. Name your repository **A02 for example** (case-sensitive).
4. Add a description, choose **Public**, and check **Initialize this repository with: Add a README file**.
5. Click **Create repository**.

*Step 2: Clone the Repository to Your Local Machine*
1. Navigate to your GitHub repository.
2. Click the green code button and copy the HTTPS link.
3. Open Git Bash and run the following command to clone the repository:
4. `git clone https://github.com/yourUCID/A02.git`
5. This will create a local copy of the repository on the machine.

**OR (optional)**

7. You can select the Add file dropdown menu and click Upload files.
8. In the Commit message field you can type your change you are making to your own repository.
9. Below the commit message fields, decide whether to add your commit to the current branch or to a new branch. If your current branch is the default branch, then you should choose to create a new branch for your commit on the last step.
10. Then click Propose changes afterwards.
11. You may skip Step 3 of the Part 2 tutorial if you choose to do the latter.

*Step 3: Create a New File on VScode and Stage Changes via GIT*
1. Open the cloned repository in VScode.
2. Create a new file (e.g., mywebpage.js).
3. Add or make changes to the content of the js file.
4. Stage the changes using:
5. `git add index.js`
6. `git add .` (for Step 2 of Add file)

*Step 4: Commit and Push Changes to GitHub*
1. Commit using: `git commit -m "Added index.js"`
2. Then push to GitHub by uploads local repository content to a remote repository (For instance "origin" is the remote repository's name and "main" is the name of that local branch to push).
3. `git push origin main`

References:

1. [Free Online Git Book](https://git-scm.com/book/en/v2)
2. [Adding a file to a repository](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
3. GitHub Sign-up Page: https://github.com/signup
4. VScode Download Page: https://visualstudio.com/Download
5. Git Official Website: https://git-scm.com/downloads/win

Bold each of the Glossary words as you use them.  Bold ONLY the glossary word.

    Branch  A separate line of development in a repository, allowing you to work on different features or fixes without affecting the main codebase.

    
    Clone The process of creating a local copy of a repository from a remote source, such as GitHub.
    
    **Commit** A snapshot of changes made to files in a repository.
    
    Fetch The process of retrieving updates or changes from a remote repository to your local copy without merging them into your work.
    
    **GIT** A version control system that tracks changes to files and allows multiple people to collaborate on projects.
    
    **GitHub** A web-based platform for hosting Git repositories, enabling collaboration, version control, and issue tracking.
    
    Merge The process of integrating changes from one branch into another, combining the work done in both lines of development.
    
    Merge Conflict Occurs when changes to the same part of a file are made in different branches, and Git cannot automatically merge them.
    
    Push The action of sending your committed changes from your local repository to a remote repository, such as GitHub.
    
    **Pull** The action of retrieving and merging changes from a remote repository into your local repository.
    
    Remote A version of a repository that is hosted on a server (e.g., GitHub). It allows collaborators to access and work on the same project.
    
    **Repository** A storage location for your project’s files and version history. It can be local (on your computer) or remote (on platforms like GitHub).

    
    
    
    A02
