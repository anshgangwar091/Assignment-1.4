Step 1: Install Git & Verify
1. If you haven't already, download and install Git from git-scm.com.

2. Open your terminal and verify the installation by running:
git --version

Step 2: Open the Terminal in the Project Folder
1. Open your terminal (or VS Code terminal) and navigate to your project folder (web-development-practice from the previous assignment):
cd path/to/web-development-practice

Step 3: Initialize the Git Repository
1. Convert the local folder into a Git repository by running:
git init

Step 4: Configure Git Username and Email
1. Set up your global credentials so your commits are associated with you:
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Steps 5, 6 & 7: Create Files and Make 3 Meaningful Commits
You need to make at least 3 distinct, meaningful commits. Follow these steps:

Commit 1: Create the main HTML structure
1. Create or open index.html and add some basic HTML code.

2. Check the status, stage the file, and commit:
git status
git add index.html
git commit -m "feat: add initial index.html structure"

Commit 2: Add a CSS stylesheet
1. Create a style.css file and link it inside your index.html.

2. Stage and commit the changes:
git status
git add style.css index.html
git commit -m "style: add basic styling with style.css"

Commit 3: Add a JavaScript file
1. Create a script.js file and link it inside your index.html.

2. Stage and commit the final changes:
git status
git add script.js index.html
git commit -m "feat: add script.js for interactivity"

How to View Your Commit History
To see the history of your three commits in the terminal, run:
git log --oneline


