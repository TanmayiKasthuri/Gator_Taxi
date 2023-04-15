# ADS_PROJECT
pushing to git- 
1) Install git from chrome
2) Run the installer and follow the installation wizard to install Git on your system. Make sure to select the option to add Git to your system's PATH environment variable during the installation process.
To complete that
Open the Windows Start menu and search for "Environment Variables".
Click on "Edit the system environment variables".
Click on the "Environment Variables" button.
In the "System Variables" section, scroll down and locate the "Path" variable, then click on the "Edit" button.
Click on the "New" button and add the path to the Git executable file. The default path for Git installation on Windows is C:\Program Files\Git\bin.
Save the changes and restart your command prompt.
3) Now, try running the git --version command again in the command prompt. It should recognize the git command and display the version of Git that is installed on your system.
4) Now follow the following commands
echo "# ADS_PROJECT" >> README.md: This command creates a new file called "README.md" in your current directory and adds the text "# ADS_PROJECT" to the file.
git init: This command initializes a new Git repository in your current directory.
git add README.md: This command stages the "README.md" file to be committed to the repository.
git commit -m "first commit": This command creates a new commit with the message "first commit" and adds the staged changes (in this case, the "README.md" file) to the repository.
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com" to set your account's default identity.
git branch -M main: This command renames the default branch from "master" to "main". This is a recent convention in the Git community to use more inclusive language.
git remote add origin https://github.com/TanmayiKasthuri/ADS_PROJECT.git: This command adds a new remote repository called "origin" with the URL "https://github.com/TanmayiKasthuri/ADS_PROJECT.git". This is the URL for the repository you want to push your code to.
git add .
git commit -m "commit message"
git branch : This is executed to see git's branch is main
git push origin main : This will push the changes from your local 'main' branch to the 'main' branch of the remote repository.
THE PROJECT IS PUSHED TO THE GITHUB
5) Run the project with command line argument python gatorTaxi.py input.txt