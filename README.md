# Git Assignment - Rohafzal

a. What is an issue?
GitHub issue is a valuable tool that enables teams to track and discuss tasks, ideas, and problems directly within a repository specific to a project. An issue offers a more focused alternative to email or Slack, with all discussions accessible to collaborators for transparency. Issues remain available even after being closed, allowing for future reference. They can be assigned, labeled, and discussed, making them an effective project management resource for organizing and prioritizing work.

b. What is a pull request?
A pull request (PR) in Git and GitHub is a feature thrugh whcih you can inform repository owners and maintainers about changes you've made in a branch or fork. By opening a new pull request, you ask that your changes be merged into the main repository. This process allows others to review, discuss, and possibly change the code before it is merged, helping to maintain quality and consistency.

c. Describe the steps to open a pull request?
Create a Branch: Create a new branch in local repository, where the changes will be made, by the following command: git checkout -b <branch name>
Make Changes: Make the desired changes to your code in this branch.
Add these changes by: git add 
Commit the Changes: Once the changes have been made,commit them using the command : git commit -m "your commit message".
Push the Branch to GitHub: Push the new branch to GitHub using the command: git push -u origin <branch name>.
Open a Pull Request by following the steps outlined below:
Go to your repository on GitHub.
Click on the 'Pull request' tab and create a pull request from your newly pushed branch (which has the changes) to the main branch of your repository.
Add a title and description for your pull request explaining what changes have been made.
Pull requests are usually created from the new branch to the main branch of the repository (changes from the new branch are merged into the main branch so make sure you choose the branches carefully).
Click "Create pull request" to submit it for review.
Review and Merge: AFter the review, make any requested changes, and once approved, the pull request can be merged into the main branch.

d. Describe the steps to add a collaborator to a repository (share write permissions)

Navigate to your repository on GitHub you want to add a collaborator to.
Click on the "Settings" tab of the repository.
On the left sidebar, click on "Collaborators" tab under Access.
Click the "Add people" button.
Enter the GitHub username or email of the person you want to add as a collaborator.
Select the person from the dropdown list and click "Add."
Lastly, you can choose the level of access (Write,share etc) you want to give the collaborator.

e. What is the difference between git and GitHub?
Git is a version control system that issed to track changes in source code during software development. It allows multiple developers to work on a project simultaneously without interfering with each other's work. Git stores snapshots of files in your project directory. If there is no change, Git doesn't store the file again and links to the previously stored identical file.
GitHub is a web-based platform that uses Git for version control but also provides additional features like issue tracking, pull requests, and collaboration tools. It hosts repositories and provides an interface for teams and developers to collaborate on projects.allowing them to review each other's work and merge changes to source code. 

f. What does git diff do?
git diff is a command that can be used to compare the differences between various states of your repository. It shows the changes in your working directory against the staging area and displays what has been added, removed, or modified in the files. This helps in reviewing changes before committing them. Nothing is shown if there are no differences.

g. What is the main branch?
The main branch (previously known as master) is the primary branch in a Git repository. This branch has the production-ready code. New changes that are made in differenr branches are eventually merged into the main branch after being reviewed and tested.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
No, it’s generally not recommended to push changes directly into the main branch, especially in collaborative projects. Instead, you should:
Always create a new branch for your changes.
Make and commit your changes to that new branch.
Open a pull request and wait for the reviers for feedback to merge your changes into the main branch.
This workflow ensures that the changes are reviewed and tested before they become part of the main codebase, which helps maintain the quality and stability of the project.