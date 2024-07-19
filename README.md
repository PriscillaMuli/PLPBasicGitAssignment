# PLPBasicGitAssignment

Task 1: Repository Setup

1. GitHub Repository Creation:

    Log in to your GitHub account.
    Click on the + icon in the upper-right corner and select New repository.
    Name the repository PLPBasicGitAssignment.
    Optionally, add a description.
    Check the box for Initialize this repository with a README.
    Click Create repository.

Task 2: Local Setup

2. Local Folder Setup:

    Create a new folder on your local machine. You can name it PLPBasicGitAssignment for consistency.
    Open a terminal or command prompt and navigate to the folder:

    bash

    cd path/to/PLPBasicGitAssignment

3. Git Initialization:

    Initialize a new Git repository in the folder:

    bash

    git init

4. Connecting to GitHub:

    Link your local repository to the GitHub repository:

    bash

    git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git

    Replace https://github.com/your-username/PLPBasicGitAssignment.git with the actual URL of your GitHub repository.

Task 3: Making Changes

5. Create a File:

    Inside your local folder, create a new text file named hello.txt.
    Open hello.txt and add the following content:

    Hello, Git!

6. Committing Changes:

    Stage the new file:

    bash

git add hello.txt

Commit the changes:

bash

    git commit -m "Add hello.txt with a greeting"

Task 4: Pushing to GitHub

7. Pushing to GitHub:

    Push the committed changes to your GitHub repository:

    bash

    git push -u origin main

Task 5: Verification

8. Verify on GitHub:

    Visit your GitHub repository in a web browser.
    Confirm that the hello.txt file and the commit message "Add hello.txt with a greeting" are visible.
