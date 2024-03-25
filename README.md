# mapstruct-auth0

https://github.com/veerachandra/mapstruct-auth0

Step 1: Initialize a Git repository

Open your terminal or command prompt.
Navigate to the root directory of your Spring Boot application using the 'cd’ command.
Run the following command to initialize a new Git repository:
git init
Step 2: Create a GitHub repository

Go to the GitHub website (https://github.com) and sign in to your account.
Click on the “+” button in the top-right corner of the screen and select “New repository.”
Provide a repository name, optional description, and choose the repository visibility (public or private).
Click “Create repository” to create the new repository.
Step 3: Connect your local repository to the GitHub repository

On the GitHub repository page, you will see the repository URL. Copy it to your clipboard.
In your terminal or command prompt, navigate to your Spring Boot application’s root directory.
Run the following command, replacing <repository_url> with the repository URL you copied:
git remote add origin <repository_url>
Step 4: Stage and commit your code changes

Use the following command to stage all the changes in your Spring Boot application:
git add .
This command adds all modified and new files to the staging area.

Next, commit the changes using the following command:

git commit -m "Initial commit"
Replace “Initial commit” with a meaningful commit message describing the changes you made.

Step 5: Push your code to GitHub

Finally, push your local repository to GitHub using the following command:
git push -u origin master
The -u option sets the upstream branch, and origin master specifies the branch you want to push to (in this case, the master branch).

Step 6: Verify your code on GitHub

Refresh your GitHub repository page, and you should see your Spring Boot application’s code and commit history.
