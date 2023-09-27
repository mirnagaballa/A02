Part 1: Directions on Using WebStorm
Step 1: Install WebStorm
Go to the JetBrains website to download WebStorm: WebStorm Download
Follow the installation instructions specific to your operating system.
Step 2: Configure Git in WebStorm
Launch WebStorm.
Go to File > Settings (on Windows) or WebStorm > Preferences (on macOS).
In the Settings/Preferences dialog, navigate to Version Control > Git.
Ensure that the path to the Git executable is correctly set. If not, browse and select the Git executable on your system.
Click OK to save your Git settings.
Step 3: Create a New Project
Click on File > New > Project.
Choose your project type and location.
Click Create.
Step 4: Initialize a Git Repository
Inside your project, right-click on the root folder.
Select Git > Initialize Repository.
Confirm the location of your Git executable if prompted.
Click OK to initialize the Git repository.
Step 5: Create and Commit Changes
Create or modify files in your project.
Right-click on the file or folder you want to commit.
Select Git > Add to stage the changes.
Right-click again and choose Git > Commit Directory.
Enter a commit message that describes your changes.
Click Commit to save your changes.
Step 6: Connect to GitHub
Go to GitHub and log in or create an account.
Click the + sign in the top right corner and select New Repository.
Follow the on-screen instructions to create a new repository on GitHub.
Copy the repository URL provided (e.g., https://github.com/yourusername/your-repo.git).
Step 7: Link Your Local Repository to GitHub
In WebStorm, go to File > Settings (on Windows) or WebStorm > Preferences (on macOS).
Navigate to Version Control > Git and ensure that your Git executable is set.
Go to Version Control > GitHub.
Click + to add a new GitHub account and enter your GitHub credentials.
Click OK to save your GitHub settings.
In the GitHub settings, click + again to add your GitHub repository by pasting the URL.
Click OK to confirm.
Step 8: Push Your Local Repository to GitHub
Right-click on your project root in WebStorm.
Select Git > Repository > Push.
Choose your GitHub repository as the target.
Click Push to upload your local changes to GitHub.

Part 2: Glossary
Branch: A parallel version of a repository, allowing for separate development and isolation of changes.
Clone: Creating a local copy of a remote repository.
Commit: Saving changes to a Git repository with a descriptive message.
Fetch: Retrieving changes from a remote repository to the local repository without applying them. 
Git: A distributed version control system used for tracking changes in code.
GitHub: A web-based platform for hosting and collaborating on Git repositories.
Merge: Combining changes from one branch into another.
Merge Conflict: Occurs when Git cannot automatically merge changes and requires manual resolution.
Push: Sending local commits to a remote repository.
Pull: Retrieving changes from a remote repository and applying them to the local repository.
Remote: A remote repository hosted on a server or platform like GitHub.
Repository: A storage location where Git tracks changes and stores code and related files.
