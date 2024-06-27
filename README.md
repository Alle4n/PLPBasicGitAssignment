# PLPBasicGitAssignment
Git Basics
Item 1: GitHub Repository Creation
1.	Logging into GitHub:
    o	I logged in to my GitHub account.
2.	Creating a New Repository:
    o	I created a new repository on GitHub called "PLPBasicGitAssignment".
    o	I made sure to initialize it with a README file.

Item 2: Local Setup
1.	Setting Up a Local Folder:
    o	I created a new folder on my local machine named "PLPBasicGitAssignment".
2.	Initializing Git:
    o	I opened my terminal and navigated to the "PLPBasicGitAssignment" folder.
    o	I initialized a new Git repository there by running git init.

Item 3: Making Changes
1.	Creating and Editing Files:
    o	Inside my local folder, I created a text file named hello.txt.
    o	I added a simple greeting message, "Hello, Git!", to hello.txt.
2.	Committing Changes:
    o	I staged the changes to hello.txt using git add hello.txt.
    o	I committed the changes with a descriptive message using git commit -m "Add hello.txt with a greeting".

Item 4: Pushing to GitHub
1.	Connecting to GitHub:
    o	To link my local repository to the GitHub repository I created earlier, I ran git remote add origin <repository-url>, replacing <repository-url> with the actual URL of my GitHub repository.
2.	Pushing Changes:
    o	I pushed the committed changes from my local repository to GitHub using git push -u origin main.
3.	Debugging Errors
    o	I encountered this this error “error: failed to push some refs to..........”
    o	In order to solve it I had to pull the  github repo to my local machine using command ‘git pull origin main’
    o	And then I had to merge the branches using command ‘git merge origin/main --allow-unrelated-histories’
    o	Then I pushed the file again using git push -u origin main.

Item 5: Verification
1.	Checking GitHub:
    o	I opened my GitHub repository in a web browser.
    o	I verified that the hello.txt file and the commit message were visible on the repository page.

